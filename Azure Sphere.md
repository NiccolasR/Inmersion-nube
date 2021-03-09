# Esfera azul
Azure Sphere crea una solución de IoT de extremo a extremo altamente segura para los clientes que abarca todo, desde el hardware y el sistema operativo del dispositivo hasta el método seguro de enviar mensajes desde el dispositivo al centro de mensajes. Azure Sphere tiene funciones de seguridad y comunicación integradas para dispositivos conectados a Internet.

**Azure Sphere viene en tres partes:**

- La primera parte es la unidad de microcontrolador (MCU) Azure Sphere, que es responsable de procesar el sistema operativo y las señales de los sensores conectados. La siguiente imagen muestra la MCU Seed Azure Sphere MT3620 Development Kit, uno de varios kits de inicio diferentes que están disponibles para la creación de prototipos y el desarrollo de aplicaciones de Azure Sphere.

- La segunda parte es un sistema operativo (SO) Linux personalizado que maneja la comunicación con el servicio de seguridad y puede ejecutar el software del proveedor.

- La tercera parte es Azure Sphere Security Service, también conocido como AS3. Su trabajo es asegurarse de que el dispositivo no haya sido comprometido de forma maliciosa. Cuando el dispositivo intenta conectarse a Azure, primero debe autenticarse a sí mismo, por dispositivo, lo que hace mediante la autenticación basada en certificados. Si se autentica con éxito, AS3 verifica para asegurarse de que el dispositivo no haya sido manipulado. Una vez que ha establecido un canal de comunicación seguro, AS3 envía al dispositivo cualquier SO o actualizaciones de software aprobadas desarrolladas por el cliente.

Una vez que el sistema Azure Sphere ha validado la autenticidad del dispositivo y lo ha autenticado, el dispositivo puede interactuar con otros servicios de Azure IoT enviando información de error y telemetría.
