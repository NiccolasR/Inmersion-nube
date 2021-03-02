Cuándo usar Azure Container Instances o Azure Kubernetes Service
-Si desea ejecutar varias instancias de una aplicación en una sola máquina host, los contenedores son una excelente opción.

¿Qué son los contenedores?
- Son un entorno de virtualización. 
- Puede ejecutar varios contenedores en un solo host físico o virtual.
- No administra el sistema operativo de un contenedor.
- Los contenedores son livianos y están diseñados para ser creados, escalados y detenidos dinámicamente.
- Puede reiniciar rápidamente en caso de un bloqueo o una interrupción del hardware.
- Uno de los motores de contenedores más populares es Docker, que es compatible con Azure.

¿Cómo administrar contenedores?
-A través de un orquestador de contenedores, que puede iniciar, detener y escalar instancias de aplicaciones según sea necesario.

Azure Container Instances 
- Ofrece la forma más rápida y sencilla de ejecutar un contenedor en Azure sin tener que administrar máquinas virtuales o adoptar servicios adicionales.

Azure Kubernetes Service (AKS).
- Es un servicio de orquestación completo para contenedores con arquitecturas distribuidas y grandes volúmenes de contenedores.
- La orquestación es la tarea de automatizar y administrar una gran cantidad de contenedores y cómo interactúan.


Azure Functions
- La computación sin servidor es la abstracción de servidores, infraestructura y sistemas operativos. 
- Con la computación sin servidor, Azure se encarga de administrar la infraestructura del servidor y la asignación y desasignación de recursos según la demanda. 
- La infraestructura no es su responsabilidad. 
- La escala y el rendimiento se gestionan automáticamente. 
- Solo se le facturarán los recursos exactos que utilice.

La computación sin servidor incluye
- Abstracción de servidores
- Escala basada en eventos 
- Microfacturación

Azure tiene dos implementaciones de computación sin servidor:

- Azure Functions : las funciones pueden ejecutar código en casi cualquier lenguaje moderno.
- Azure Logic Apps : las aplicaciones lógicas están diseñadas en un diseñador basado en web y pueden ejecutar la lógica desencadenada por los servicios de Azure sin escribir ningún código.
