# arquillian_poc

Prueba de concepto de Arquillian Cube. 

Crear una imagen de docker que contiene un jar Spring Boot , deployarla y lanzar un test contra un Rest service.

Debes tener un máquina virtual creada llamada default

Ejecutar en el terminal (para decirle a docker que hable con esta máquina virtual):

> docker-machine env default

Finalmente si quieres conectar tu shell a la máquina virtual

> eval "$(docker-machine env default)"
