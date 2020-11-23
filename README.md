# Practica-sockets
Realizar un programa en dos partes(cliente y servidor) en donde realice la siguiente tarea:

SERVIDOR:
1.- Abrir un socket que acepte conexiones en la ip local (127.0.0.1) en el puerto 9000
2.- El servidor queda a la espera de conexiones
3.- Cuando un cliente se conecta el servidor muestra un mensaje en la pantalla "CLIENTE CONECTADO"
4.- El servidor envía un mensaje de texto al cliente a través de la conexión "HOLA SOY EL SERVIDOR"
5.- Al desconectarse un cliente el servidor muestra un mensaje "CLIENTE DESCONECTADO"

CLIENTE
1.- Se conecta a través de un socket al programa servidor (127.0.0.1 en el puerto 9000)
2.- Al recibir el mensaje de bienvenida del servidor lo imprime en pantalla
3.- Se desconecta del servidor y cierra la conexión.
