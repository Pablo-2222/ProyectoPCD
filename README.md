# ProyectoPCD
## Una implementación del parchís en multijugador
Juego del parchis
  Crear las clases con sus atributos
    Tablero
      Casillas
      Ficha
  Crear funciones  para el funcionamineto del juego
    Tablero
      Void PrepararTablero()Crear las listas de las fichas y de las casillas
      Boolean ComprobarMovimientoFicha(int jugador, int ficha, int tirada) Mira si hay barrera por el camino y devuelve False si no se puede hacer. Tambien comprueba si la ficha puede salir de casa en el caso de que lo               intente
      Ficha MoverFicha((int jugador, int ficha, int tirada)Actualiza la posicion de la ficha, la lista de casillas y si hay barrera en dicha casilla. Hay que tener en cuenta de que si la ficha sale de casa antes hay que             darle una posicion dependiendo del color. Se me ha ocurrido que puede devolver una ficha que seria la ficha que come para que el servidor avise cada vez que se come una ficha.
      Void MostrarTablero()Aunque sea una de forma mala para comprobar el funcionamiento
Servidor/Cliente:
  Cliente: Es avisado de que es su turno, se le pide que tire los dados pulsando alguna tecla y se le informa de su tirada, se le muestra del tablero, y elige una ficha a mover, se le envia al server el numero jugador,         numero ficha y numero tirada. El server comprueba que el movimineto sea valido y si volvemos a que eliga ficha(Caso en el que no ueda mover nada???)
  Server: Esperar y avisar cuando alguien se conecte o desconecte, cuando esten los 4 empezar la partida, avisar al jugador que sea su turno(se podria comprobar que este conectado), realizar loscambios y comprobaciones con     los datos proporcionados por el jugador. Cuando un jugador haya acabado que le envie un mensaje al server y se acabe la partida.
  

Opcional: 
  Mostrar el tablero de una forma mejor(Se puede mirar para hacerlo con colores como en python en programacion)
  Mejoras a la hora de conectar a los jugadores como que eligan nombren o que avisen cuando esten listos para jugar
    
      
    
      
      
