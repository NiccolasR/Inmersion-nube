# Funciones de Azure
Con el servicio Azure Functions , puede hospedar un solo método o función mediante el uso de un lenguaje de programación popular en la nube que se ejecuta en respuesta a un evento. Un ejemplo de un evento podría ser una solicitud HTTP, un nuevo mensaje en una cola o un mensaje en un temporizador.

Debido a su naturaleza atómica, Azure Functions puede servir para muchos propósitos en el diseño de una aplicación. Las funciones se pueden escribir en muchos lenguajes de programación comunes, como C #, Python, JavaScript, Typecript, Java y PowerShell.

Azure Functions escala automáticamente y los cargos se acumulan solo cuando se activa una función. Estas cualidades hacen de Azure Functions una opción sólida cuando la demanda es variable. Por ejemplo, es posible que reciba mensajes de una solución de IoT que supervisa una flota de vehículos de reparto. Es probable que reciba más datos durante el horario comercial. Azure Functions puede escalar horizontalmente para adaptarse a estos tiempos de mayor actividad.

Una función de Azure es un entorno sin estado. Una función se comporta como si se reiniciara cada vez que responde a un evento. Esta función es ideal para procesar datos entrantes. Y si se requiere el estado, la función se puede conectar a una cuenta de almacenamiento de Azure.

Azure Functions puede realizar tareas de orquestación mediante el uso de una extensión llamada Durable Functions, que permite a los desarrolladores encadenar funciones juntas mientras se mantiene el estado.

La solución Azure Functions es ideal cuando solo le preocupa el código que ejecuta su servicio y no la plataforma o infraestructura subyacente. Usas Funciones con más frecuencia cuando necesitas realizar un trabajo en respuesta a un evento. Lo hace a menudo a través de una solicitud REST, un temporizador o un mensaje de otro servicio de Azure, y cuando ese trabajo se puede completar rápidamente, en segundos o menos.

Link: https://azure.microsoft.com/es-mx/services/functions/
