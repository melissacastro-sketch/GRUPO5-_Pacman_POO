# GRUPO5-_Pacman_POO
Proyecto de Programación Orientada a Objetos - Documentación del juego Pacman del Grupo 5


Integrantes: 1- Juan Pablo Henríquez Montano (Pantalla de Game Over con opción de reinicio (tecla R))                                                                         
             2- Diego Alessandro Romero Montoya (Elemento especial (comida doble / escudo / power-up / doble salto / power-pellet parpadeante)                            
             3- Lisseth Abigail Martínez Martínez (Nuevo tipo de obstáculo o enemigo con comportamiento diferente)                                                    
             4- Cristy Marinela De León Contreras (Mejora visual del HUD (nivel, velocidad, récord o porcentaje de progreso)                                                
             5- Melissa Rosibel Castro Rivas (Documentación del código y desarrollo del juego.)

            

         
## Descripción del juego Pacman
Pacman es un juego clásico en el que el jugador controla un personaje que debe recorrer un laberinto comiendo puntos mientras evita a los enemigos que son fantasmas. El objetivo es completar el nivel sin ser atrapado.





## Documentación del código
El proyecto está organizado en varias clases principales:

GameController: Controla la lógica general del juego.                                                                                                                
Maze: Representa el laberinto donde se desarrolla el juego.
                                                                                                                                                               Pacman: Maneja el movimiento y acciones del jugador.
                                                                                                                                                               Ghost: Controla el comportamiento de los enemigos
                                                                                                                                                                  Model: contiene la lógica del juego (Maze, Ghost, GameState).                                                                                                           
Controller: controla el flujo del juego (GameController, KeyHandler).                                                                                                        
View: maneja la parte visual (GamePanel, MazePanel).




Cada clase cumple una función específica dentro del sistema, lo que permite dividir el programa en partes más organizadas y fáciles de entender. Esta estructura facilita el mantenimiento del código, ya que si se necesita modificar alguna funcionalidad, se puede hacer directamente en la clase correspondiente sin afectar todo el proyecto. Además, esta forma de organización mejora la reutilización del código y permite que el desarrollo sea más ordenado, claro y escalable, siguiendo los principios de la Programación Orientada a Objetos.




## Uso de Programación Orientada a Objetos
En el proyecto se aplica herencia, ya que algunas clases comparten características comunes, como los enemigos del juego. También se utiliza polimorfismo, permitiendo que diferentes objetos respondan de manera distinta a las mismas acciones, como el movimiento o comportamiento dentro del juego. 




## Integrante 4 – Mejora visual del HUD (nivel, velocidad, récord o porcentaje de progreso)
Cristy Marinela de León Contreras

Usé Programación Orientada a Objetos (POO) en este código porque necesitaba organizar mejor las responsabilidades dentro del juego y hacer el sistema más claro, reutilizable y fácil de mantener. En este caso, la clase HudPanel representa un objeto específico del programa: la interfaz gráfica donde se muestra la información del jugador (puntaje, nivel y vidas). Al definirla como una clase que extiende JPanel, encapsulo todo lo relacionado con el HUD (diseño, colores, dibujo, datos) en un solo lugar, evitando mezclar esta lógica con otras partes del juego. Además, mediante el uso de métodos como paintComponent y el acceso a ctrl.getState(), aplico principios clave de la POO como encapsulación y separación de responsabilidades, ya que el HUD solo se encarga de mostrar datos, mientras que otras clases gestionan la lógica del juego. Esto permite que el código sea más ordenado, escalable (por ejemplo, si quiero cambiar el diseño sin afectar la lógica) y más fácil de entender.

el codigo se ve así:


<img width="1188" height="635" alt="image" src="https://github.com/user-attachments/assets/7fb82b0d-d09c-4708-b958-7ea9c4f52ed7" />
<img width="819" height="652" alt="image" src="https://github.com/user-attachments/assets/07a57f9c-5bec-4bcf-bbc5-df5a9721251d" />
<img width="794" height="370" alt="image" src="https://github.com/user-attachments/assets/c2f73a57-570b-4511-8fbe-2dbf41d31f97" />


Funsión del codigo ya completado:
<img width="574" height="748" alt="image" src="https://github.com/user-attachments/assets/87e9a1e3-1821-4d25-8528-65f510b7efd9" />


