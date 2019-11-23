# ontos:arquitectura extensible de servicios de minería de datos para aplicaciones móviles en 2020

Estudiantes de educación superior en informática de dos instituciones distintas colaboran para la implementación de una arquitectura extensible de servicios de minería de datos. Las operaciones de minería de datos implementadas son clasificación y agrupación. Cada servicio se diseña para insertarse en una infraestructura basada en los estándares de la arquitectura modelo-vista-controlador para aplicaciones móviles en 2020. 

  - vista: Autómata interfaz codificador de estructuras de datos de entrada y despliegue 
     -- controles: reciben los parámetros de usuario requeridos y desplieguen 
  , algunos eventos pueden ser respondidos con scripts desde la vista. Típicamente se solicita al controlador que se ejecute un proceso en el servidor que obtenga los datos del modelo y responder así la solicitud; pero en el patrón tecnológico del internet de las cosas se puede solicitar al controlador que envíe los parámetros de usuario a una base de conocimiento para que codifique un programa en tiempo ejecución. Dicho programa se envía en una cadena de texto como respuesta de la base de conocimiento al controlador, mismo que podría ejecutarlo, enviarlo a la vista para ejecutarlo como script mediante el objeto json.parse del Document Object Model) enviarlo al modelo para que se ejecute del lado del servidor de datos y recibir la respuesta para a su vez enviarla a la vista.Ee

La arquitectura ONTOS codifica tres estructuras de conocimiento: árboles de decisión, redes bayesianas y autómatas finitos.
