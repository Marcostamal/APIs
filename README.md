# Que es una API y como utilizar la libreria requests de python
## Introduccion
Hola, ¿Como estas? el dia de hoy mediante este repositorio te estare explicando lo que es una API, como utilizar la libreria requests de python y algunas otras cosas que deberias saber para entender un poco mas acerca de este tema.

## Que es una API
Una API ("Interfaz de programacion de aplicaciones") es un mecanismo que permite a dos componentes de software comunicarse entre si mediante un conjunto de definiciones y protocolos.
 
En el contexto de las API, la palabra aplicación se refiere a cualquier software con una función distinta. La interfaz puede considerarse como un contrato de servicio entre dos aplicaciones. Este contrato define cómo se comunican entre sí mediante solicitudes y respuestas. La documentación de su API contiene información sobre cómo los desarrolladores deben estructurar esas solicitudes y respuestas.

La arquitectura de las API suele explicarse en términos de cliente y servidor. La aplicación que envía la solicitud se llama cliente, y la que envía la respuesta se llama servidor. En el ejemplo del tiempo, la base de datos meteorológicos del instituto es el servidor y la aplicación móvil es el cliente. 

Esta es una breve definicion sobre lo que es una API si quieres saber un poco mas sobre ellas dale click a este enlace de AWS: [Mas informacion aqui](https://aws.amazon.com/es/what-is/api/)

## La libreria Requests de Python

Esta libreria lo que nos permite es hacer peticiones en formato HTTP a un servidor para conseguir alguna transferencia de informacion, por lo genaral este tipo de aplicaciones tienen una documentacion en la cual detalla como se deben de hacer estas peticiones y la respuesta que recibira. Esta libreria no viene por defecto con python por lo que tendras que instalarla [libreria requests](https://pypi.org/project/requests/)

