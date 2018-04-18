# EJERCICIO T4.5

## Probar las diferentes maneras de redirección HTTP. ¿Cuál es adecuada y cuál no lo es para hacer balanceo de carga global? ¿Por qué?

Después de buscar sobre los distintos tipos de redirecciones HTTP, he encontrado que existen 2 tipos de redirección:

-> 301: son comandos que permiten enviar a usuarios y buscadores de una URL  a otra automáticamente. Por esta razón son un recurso esencial para el mantenimiento de tu web.

-> 302: señala una redirección temporal.

Para realizar un balanceo de carga es mejor la 302, ya que permite redirigir el tráfico a direcciones temporales y no una permanente. 
