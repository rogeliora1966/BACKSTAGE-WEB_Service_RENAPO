# **Proceso de actualización de certificado para el servicio de consultas de RENAPO**.

## Descripción
Servicio que permite acreditar, la renovación del certificado de seguridad de RENAPO para el dominio curp.gob.mx.

### ¿Quién y cómo se puede solicitar?
Lo puede solicitar personal de las Unidades Administrativas que utilicen o hayan utilizado algún Sistema/Aplicación administrado por la DGTIC, que se recibe por medio de la Mesa de Servicios a través de un correo electrónico a la cuenta mesa.servicios@agricultura.gob.mx. turnado por un Director de Área o superior.

### Tiempo de atención
Tiempo de primer contacto:  5 días hábiles
Tiempo de atención: 1 día hábil para RENAPO, 1 días hábil para el SAT.

Métricas y KPIs
<!-- Describir las métricas y KPIs para este servicio que ayuden a medir el desempeño y la calidad del mismo.-->

Métricas: 
`actualizar
               Despliegue de certificado en el servicio de consultas de RENAPO una vez recibido el certificado vigente.         
```
KPI:
```
           % en relacion al numero de incidencias o inconsistencias en la vigencia del cetificado de RENAPO 
           % de bajas índice de estatus de mortalidad (Estatus de supervivencia)
           % de población actualizada
###   BACKSTAGE
**Procedimiento de actualización de certificado para el servicio de consultas de RENAPO**.

Objetivo:

Establecer los pasos para la correcta atención de las solicitudes relacionadas con la actualización de certificados del WEBservice a través del servicio de consultas de RENAPO, asegurando una gestión eficiente y el cumplimiento de los procedimientos internos.

1. Recepción de Solicitud
	
	1.1. Mesa de Servicios crea un ticket de atención para cada solicitud recibida, donde se adjunta el 		Certificado entregado 	por la RENAPO, registrando la información relevante para su seguimiento.
	
   	1.2. La solicitud es recibida por parte de Mesa de Servicios a través del correo electrónico institucional: 	mesa.servicios@agricultura.gob.mx, y remite el ticket a la Dirección del agente del enlace administrativo 
	de la Subdirección de Operación y Administración de Sistemas.

2. Validación de Observaciones.

	2.1. Mesa de Servicios revisa la solicitud y verifica, remite al area involucrada para la valoración de las 	observaciones que impidan su atención 		inmediata.
 
	2.2. En caso de que se detecten observaciones, Mesa de Servicios contacta al área requirente para
	solicitar los datos adicionales o correcciones necesarias para poder proceder con la solicitud.
 
	2.3. Si no se detectan observaciones, Mesa de Servicios emite un número de folio que se utilizará para dar seguimiento a la solicitud por parte de la del 	agente del enlace administrativo de la Subdirección de Operación y Administración de Sistemas.y remite el ticket 	

3. Validación del Solicitante.
	
 	3.1. El enlace administrativo de la Subdirección de Operación y Administración de Sistemas recibe la 		solicitud y valida si el solicitante es 	personal involucrado en la DGTIC de la Secretaría.
	
	3.2. Si el solicitante es personal involucrado en la Secretaría, la Subdirección de Operación y 		Administración de Sistemas continúa con el 	trámite de actualización del certificado.
	
	
4. Ejecución de la Solicitud.
	
   	4.1. Una vez validada la solicitud, la Subdirección de Operación y Administración de Sistemas procede con la 	ejecución del proceso de actualización del 	certificado vigente.

	
5. Notificación y Cierre de Ticket
	
 	5.1. Una vez finalizada la actualización del certificado, la Subdirección de Operación y Administración de 	Sistemas notifica la conclusión del proceso 	para su validación a través la funcionalidad de del servicio de 	WEBService.

	5.2. Mesa de Servicios cierra el ticket en la plataforma, completando así el ciclo del servicio solicitado.


- **Diagrama del Procedimiento**
[Renapo.pdf](https://github.com/user-attachments/files/19982005/Renapo.pdf)

```plaintext
+-------------------------------------------+
|       Recepción de correo electrónico     |
|           en la cuenta                    |
|     mesa.servicios@agricultura.gob.mx     |
+--------------------+----------------------+
                     |
                     v
       +------------------------------------------+
       |Mesa de Servicios crea un numero de ticket|
       +------------------------------------------+
                     |
                     v
         +-------------------------+
         | ¿Existen observaciones?  |
         +-----------+-------------+
             | Sí            | No
             v               v
   +------------------+    +----------------------+
   | Informar área    |    |  Emitir número de    |
   | mesa de ayuda    |    |    folio y dar       |
   |  requirente sobre|    |  seguimiento al      |
   | datos necesarios |    | enlace administrativo|
   +------------------+    +----------------------+
             |                         |
             v                         v
     +-------------------+   +------------------------------+
     | Enlace recibe la  |   | Enlace valida si es personal |
     | solicitud y valida|   | de la Secretaría             |
     | si es personal de |   +------------------------------+
     | la Secretaría     |                    |
     +-------------------+                    |
             | No                             | Sí
             v                                v
   +----------------------------+  +------------------------------------+
   | Enlace genera respuesta    |  |         RENAPO entrega el          |
   | respuesta y notifica       |  | certificado vía correo electrónico |
   | a mesa de servicios        |  +------------------------------------+
   +----------------------------+             |
             |                                v
             v                     +---------------------------+
    +------------------+           | Procede con actualización |
    | Mesa de Servicios|<----------|     del certificado       |
    | notifica vía     |           |         vigente           |
    | plataforma       |           +---------------------------+
    +------------------+                    
             |                              
             v                    
       +-----------------------+  
       | Cerrar ticket en Mesa  |  
       | de Servicios           |  
       +-----------------------+
```

Este diagrama visual,  muestra las decisiones y las acciones correspondientes en cada etapa.


