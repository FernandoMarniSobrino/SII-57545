Laboratorio de Sistemas Informaticos Industriales:

Durante el desarrollo de estas practicas, el objetivo sera aprender a utilizar la terminal de linux y conocer las maneras de acceder, editar y crear distintas carpetas y procesos dentro del ordenador. Para ello, iremos desarrollando un juego que se basa en el tenis. Al mismo tiempo que vamos conociendo comandos para poder trabajar de una forma mas comoda en la terminal.

Para la primera practica, hemos implementado el movimiento de las raquetas y de la pelota para poder jugar dos personas en el mismo ordenador.

El objetivo de la segunda practica era la de implementar el uso de una tuberia FIFO al juego, con el fin de aprender a utilizar una tuberia. Ha consistido en la modificacion del codigo del archivo logger, el cual se ejecuta antes del tenis, para crear y configurar la tuberia que se utilizara en el juego. Ademas, hemos incluido que el juego se acabe cuando uno de los dos jugadores consiga 3 puntos, convirtiendole asi en el ganador del juego.

Para la tercera practica del laboratorio, el fin era trabajar con la memoria compartida entre dos procesos independientes. En nuestro caso seria entre el juego de tenis y la clase bot que controlara al jugador 1 del juego. Para ello, hemos creado mediante la funcion mmap la union entre los dos procesos dentro de la memoria. Una vez hecho la conexion, teniamos que darle funcionalidad al bot, para que sepa como moverse para poder dar a la pelota mediante la utilizacion de la memoria compartida entre el tenis y el bot.
