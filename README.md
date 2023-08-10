# Que es una API y como utilizar la libreria requests de python
## Introduccion
Hola, ¿Como estas? el dia de hoy mediante este repositorio te estare explicando lo que es una API, como utilizar la libreria requests de python y algunas otras cosas que deberias saber para entender un poco mas acerca de este tema.

## Que es una API
Una API ("Interfaz de programacion de aplicaciones") es un mecanismo que permite a dos componentes de software comunicarse entre si mediante un conjunto de definiciones y protocolos.
 
En el contexto de las API, la palabra aplicación se refiere a cualquier software con una función distinta. La interfaz puede considerarse como un contrato de servicio entre dos aplicaciones. Este contrato define cómo se comunican entre sí mediante solicitudes y respuestas. La documentación de su API contiene información sobre cómo los desarrolladores deben estructurar esas solicitudes y respuestas.

La arquitectura de las API suele explicarse en términos de cliente y servidor. La aplicación que envía la solicitud se llama cliente, y la que envía la respuesta se llama servidor. En el ejemplo del tiempo, la base de datos meteorológicos del instituto es el servidor y la aplicación móvil es el cliente. 

Esta es una breve definicion sobre lo que es una API si quieres saber un poco mas sobre ellas dale click a este enlace de AWS: [Mas informacion aqui](https://aws.amazon.com/es/what-is/api/)

## La libreria Requests de Python

Esta libreria lo que nos permite es hacer peticiones en formato HTTP a un servidor para conseguir alguna transferencia de informacion, por lo genaral este tipo de servidores tienen una documentacion en la cual detalla como se deben de hacer estas peticiones y la respuesta que recibira. Esta libreria no viene por defecto con python por lo que tendras que instalarla [libreria requests](https://pypi.org/project/requests/)

## Codigos de estado de respuesta

Antes de ver el ejemplo practico es importante aclarar que son los codigos de estado de respuesta, estos nos van a indicar si la peticion que hemos hecho a sido satisfactoria o no, hay muchos codigos y uno con el que seguro te has topado es el famoso error 404, este codigo lo que significa es que la pagina no existe. Otro codigo interesante es el 200, este es el que esperamos optener y el que nos indicara que la peticion que hemos hecho se ha hecho correctamente.

No es necesario aprenderlos todos, solo basta con mirar cual es el primer digito del codigo para darnos una idea de lo que significa.
<p align="center">
<img src="https://static.wixstatic.com/media/850ae7_581a8111d7dd4134855ca2072370ce2d~mv2.png/v1/fill/w_640,h_406,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/850ae7_581a8111d7dd4134855ca2072370ce2d~mv2.png"  height="400"> </p>
