# eureka-server
El servidor Eureka permite registrar los microservicios que colaboran o forman la arquitectura para registrar una reserva  
Los siguientes microservicios se registran en eureka-server:  

* servicio-regitrar-reserva 
* servicio-consultar-reserva
* servicio-zuul-server

El servicio zuul tiene el rol de apiGateway centralizando y  
controlando las peticiones al interior de la estructuras de microservicios  

Para ejecutar este microservicio se necesita:  
* Sistema Operativo: Windows,MacOS, Linux,
* Maven version: 3.x+ o Gradle 4.x+
* Java : 1.8 o superior
