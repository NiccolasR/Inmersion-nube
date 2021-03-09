# Plantillas ARM
Aunque es posible escribir código imperativo en Azure PowerShell o la CLI de Azure para configurar y eliminar un recurso de Azure u orquestar una infraestructura que comprenda cientos de recursos, existe una mejor manera de implementar esta funcionalidad.

Mediante el uso de plantillas de Azure Resource Manager (plantillas ARM), puede describir los recursos que desea usar en un formato JSON declarativo. El beneficio es que toda la plantilla ARM se verifica antes de ejecutar cualquier código para garantizar que los recursos se crearán y conectarán correctamente. Luego, la plantilla organiza la creación de esos recursos en paralelo. Es decir, si necesita 50 instancias del mismo recurso, las 50 instancias se crean al mismo tiempo.

En última instancia, el desarrollador, el profesional de DevOps o el profesional de TI solo necesita definir el estado y la configuración deseados de cada recurso en la plantilla ARM, y la plantilla hace el resto. Las plantillas pueden incluso ejecutar scripts de PowerShell y Bash antes o después de que se haya configurado el recurso.
