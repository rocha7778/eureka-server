# eureka-server
El servidor Eureka permite registrar los microservicios que forman la arquitectura para registrar una reserva, tambien actua como balanceador de carga en caso tal sea necesario escalar algunos de los microservicios registrados en él.
Los siguientes microservicios se registran en eureka-server:  

* servicio-regitrar-reserva 
* servicio-consultar-reserva
* servicio-zuul-server

El servicio zul tiene el rol de apiGateway centralizando y  
controlando las peticiones al interior de la estructura de microservicios  

Para ejecutar este microservicio se necesita:  
* Sistema Operativo: Windows,MacOS, Linux,
* Maven version: 3.x+ o Gradle 4.x+
* Java : 1.8 o superior
