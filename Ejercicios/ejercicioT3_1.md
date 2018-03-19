# EJERCICIO T3.1

## Buscar con qué órdenes de terminal o herramientas gráficas podemos configurar bajo Windows y bajo Linux el enrutamiento del tráfico de un servidor para pasar el tráfico desde una subred a otra. 

* **Windows**: En Windows Server existe la opción Servicio de enrutamiento y acceso remoto. Con esta opción se puede realizar tareas de enrutamiento de tráfico de forma rápida y sencilla siguiendo los pasos del asistente de Windows Server.

* **Linux**: Para realizar el enrutamiento debemos usar órdenes de terminal.
Por lo que he estado mirando por internet hay que crear una ruta con el comando route y añadirla o borrarla con add. Si lo que queremos es mantener rutas tras reiniciar el servidor, añadimos la ruta al archivo /etc/network/interfaces (archivo en el que se guardan las rutas) mediante el comando:
**up route add -net ....**.


