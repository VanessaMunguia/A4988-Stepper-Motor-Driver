# A4988-Stepper-Motor-Driver

Tecnológico Nacional de México Instituto Tecnológico de Tijuana

               SUBDIRECCIÓN ACADÉMICA
       DEPARTAMENTO DE SISTEMAS Y COMPUTACIÓN

            SEMESTRE: ENERO – JUNIO 2023
                       
                       CARRERA:
       INGENIERÍA EN SISTEMAS COMPUTACIONALES
                       
                       MATERIA:
                SISTEMAS PROGRAMBLES
               
               TÍTULO DE LA ACTIVIDAD:
                     EXPOSICION
               
                NOMBRE Y NO.CONTROL:
       Amanda Vanessa Munguia Flores #19210525

                NOMBRE DEL MAESTRO:
                 RENE SOLIS REYES

¿QUÉ ES UN A4988?

El A4988 son controladores (drivers) que simplifican el manejo de motores paso a paso desde un autómata o procesador como Arduino. Estos controladores nos permiten manejar los altos voltajes e intensidades que requieren estos motores, limitar la corriente que circula por el motor, y proporcionan las protecciones para evitar que la electrónica pueda resultar dañada.
Para su control únicamente requieren dos salidas digitales, una para indicar el sentido de giro y otra para comunicar que queremos que el motor avance un paso. Además permiten realizar microstepping, una técnica para conseguir precisiones superiores al paso nominal del motor.
El A4988 ha alcanzado una gran popularidad en sus últimos tiempos debido a su uso en proyectos como, por ejemplo, en impresoras 3D caseras.

![image](https://user-images.githubusercontent.com/89666637/227054091-79febdd9-e5e2-492a-8434-65123abc4f59.png)  

Pueden alcanzar altas temperaturas durante su funcionamiento y es necesario disipar el calor para que el dispositivo no se dañe. Para intensidades superiores 1A en el A4988 es necesario añadir un sistema de disipación de calor, e incluso ventilación forzada. 
Disponen de protecciones contra sobreintensidad, cortocircuito, sobretensión y sobretemperatura. En general, son dispositivos robustos y fiables siempre que realicemos la conexión correctamente, e incorporemos disipación de calor si es necesario. 
Son muy empleados en una gran variedad de proyectos que requieren el uso de motores paso a paso, como máquinas de CNC, plotters, robots que dibujan, impresoras 3D, y escáneres 3D.
También son un componente frecuente en proyectos para controlar robots y vehículos, especialmente en aquellos que requieren variar de forma individual la velocidad de cada rueda, como en vehículos con omniwheel o mecannum wheels.
