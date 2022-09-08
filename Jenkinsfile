import java.time.LocalDate;
pipeline {
    agent any

    stages {
        stage('Getting day') {
            steps{
                script{
                    LocalDate fecha = LocalDate.now()
                    println 'Hoy es ' + fecha.getDayOfMonth() + "/" + fecha.getMonthValue() + "/" + fecha.getYear()
                    switch (fecha.getDayOfWeek()) {
                        case 'MONDAY':
                            stage('MONDAY'){
                                script{
                                    stage('Chiste de futbol'){
                                        println 'En la cola del mercado:' +
                                        '\n-Perdona, ¿El ultimo?' +
                                        '\n-El Celta con 17 puntos.'
                                    }
                                }
                            }
                            break;
                        case 'TUESDAY':
                            stage('TUESDAY'){
                                script{
                                    stage('Chiste de politica'){
                                        println 'Un hombre, al pasar frente al Congreso de los Diputados, escucha un tremendo griterio que salía desde la sala:' +
                                        '\n"Ladron, mentiroso, comisionista, difamador, chorizo, sinvergüenza, flojo de mierda, imbecil, timador, cabrón, corrupto, vendido, golfo, aprovechado, cara dura, falso, chupón, inutil, pesetero, estafador, vago de mierda, saqueador, gilipollas, bobo, oportunista, embaucador, tramposo, hijo de la gran puta,...........etc.' +
                                        '\nEl hombre asustado le pregunta al guardia de la entrada:' +
                                        '\n- Señor, ¿que pasa dentro?, ¿se estan peleando?' +
                                        '\n- No, responde el guardia, yo creo que estan pasando lista.'
                                    }
                                }
                            }
                            break;
                        case 'WEDNESDAY':
                            stage('WEDNESDAY'){
                                script{
                                    stage('Chiste de medicos'){
                                        println 'Llega un hombre a una farmacia y le pregunta al farmaceutico:' +
                                        '\n- ¿Tiene pastillas para los nervios?' +
                                        '\n- Si' +
                                        '\n-¡Pues tomese dos que esto es un atraco!'
                                    }
                                }
                            }
                            break;
                        case 'THURSDAY':
                            stage('THURSDAY'){
                                script{
                                    println 'Hoy es ' + fecha.getDayOfMonth() + "/" + fecha.getMonthValue() + "/" + fecha.getYear()
                                    stage('Chiste informaticos'){
                                        println 'La gente reacciona diferente cuando se pone una vacuna:' +
                                        '\nCuando es un niño: ¡AYYYY, COMO DUELE!' +
                                        '\nCuando es un joven: Duele un poquito, pero no es nada.' +
                                        '\nCuando es un hombre: No me duele nada, ni lo he notado.' +
                                        '\nCuando es un informático: La base de datos de virus ha sido actualizada'
                                    }
                                }
                            }
                            break;
                        case 'FRIDAY':
                            stage('FRIDAY'){
                                script{
                                    stage('Chiste de humor negro'){
                                        println 'Una mujer llega a casa y se encuentra a su marido esnifando cocaina:' +
                                        '\n-Antonio ¡me prometiste que no te drogarias mas!' +
                                        '\n-Lo se cariño si no voy a drogarme más solo lo de siempre.'
                                    }
                                }
                            }
                            break;
                            
                        default:
                            println '¡No hay chistes el fin de semana!'
                            break;
                    }
                }
            }
        }
    }
}
