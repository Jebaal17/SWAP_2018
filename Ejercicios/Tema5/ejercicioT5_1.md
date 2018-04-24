# EJERCICIO T5.1

## Buscar información sobre cómo calcular el número de conexiones por segundo. Para empezar, podéis revisar las siguientes webs: http://bit.ly/1ye4yHz, http://bit.ly/1PkZbLJ

Después de visitar los enlaces, se pueden obtener como conclusión 2 tipos de formas para calcular el número de conexiones por segundo:

* nginx:

![configuracion](https://github.com/Jebaal17/SWAP_2018/blob/master/Ejercicios/img/conf-nginx.png)

![test](https://github.com/Jebaal17/SWAP_2018/blob/master/Ejercicios/img/test-nginx.png)


Fórmula matemática: 

Requests per connection = handles requests / handled connections

* comando netstat:

*netstat | grep http | wc -l*

