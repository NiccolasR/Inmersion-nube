# Análisis de los criterios de decisión
# ¿Está creando un agente virtual que interactúa con seres humanos mediante el lenguaje natural?

Use *Azure Bot Service* cuando necesite crear un agente virtual para interactuar con los usuarios mediante el lenguaje natural. Bot Service integra orígenes de conocimiento, procesamiento de lenguaje natural y factores de forma para permitir la interacción entre distintos canales.
Las soluciones de Bot Service normalmente se basan en otros servicios de IA para cuestiones como la comprensión del lenguaje natural o incluso la traducción para localizar las respuestas al idioma preferido del cliente.
Antes de entrar de pleno en la creación de una experiencia de chat personalizada con Bot Service, puede que sea mejor buscar soluciones precompiladas sin código que abarquen los escenarios habituales. Por ejemplo, puede emplear QnA Maker, disponible en Azure Marketplace, para crear, entrenar y publicar un bot sofisticado que use páginas de preguntas más frecuentes, sitios web de soporte técnico, manuales de productos, documentos de SharePoint o contenido editorial a través de una interfaz de usuario fácil de usar o mediante las API de REST.
De forma similar, Power Virtual Agents se integra con Microsoft Power Platform, lo que le permite usar cientos de conectores prediseñados para la entrada de datos. Puede ampliar Power Virtual Agents si crea flujos de trabajo personalizados con Power Automate y, si la experiencia rápida le parece demasiado limitada, puede crear interacciones más complejas con Microsoft Bot Framework.

# ¿Necesita un servicio que pueda comprender el contenido y el significado de imágenes, vídeos y audios o traducir texto a un idioma diferente?

Use *Azure Cognitive Services* cuando necesite realizar tareas de uso general, como la conversión de voz en texto, la integración con búsquedas o la identificación de objetos en una imagen. Azure Cognitive Services es de uso general, lo que significa que muchos tipos diferentes de clientes pueden beneficiarse del trabajo que Microsoft ya ha llevado a cabo para entrenar y probar estos modelos y ofrecerlos de forma económica a escala.

# ¿Necesita predecir el comportamiento del usuario o proporcionar a los usuarios recomendaciones personalizadas en la aplicación?

El servicio *Azure Cognitive Services Personalizer* supervisa las acciones de los usuarios en una aplicación. Puede usar Personalizer para predecir su comportamiento y proporcionar experiencias relevantes a medida que identifique patrones de uso. De nuevo, podría capturar y almacenar el comportamiento del usuario y crear su propia solución de Azure Machine Learning personalizada para realizar estas acciones, pero este enfoque requeriría mucho esfuerzo y gastos.

# ¿La aplicación predecirá resultados futuros a partir de datos históricos privados?

Elija *Azure Machine Learning* cuando necesite analizar datos para predecir resultados futuros. Por ejemplo, supongamos que necesita analizar transacciones financieras realizadas durante años para detectar nuevos patrones que podrían ayudarle a crear nuevos productos y servicios para los clientes de su empresa y ofrecer esos nuevos servicios durante las llamadas rutinarias del servicio al cliente. Al trabajar con datos de propiedad, es probable que necesite crear un modelo de aprendizaje automático más personalizado y adaptado.

# ¿Necesita crear un modelo con sus propios datos o realizar una tarea distinta de las mencionadas anteriormente?

Use *Azure Machine Learning* para obtener la máxima flexibilidad. Los científicos de datos y los ingenieros de IA pueden usar las herramientas con las que están familiarizados y los datos que les proporcione para desarrollar modelos de aprendizaje profundo y de aprendizaje automático adaptados a sus requisitos particulares.

# Más información
- Para ver una lista exhaustiva de los servicios disponibles en Azure Cognitive Services, consulte ¿Qué es Azure Cognitive Services? https://docs.microsoft.com/es-es/azure/cognitive-services/what-are-cognitive-services
- El servicio Personalizer de Cognitive Services se mencionó como una posible solución para uno de los escenarios. Para obtener más información, consulte Personalizer de Cognitive Services. https://azure.microsoft.com/es-mx/services/cognitive-services/personalizer/
- Azure Language Understanding (LUIS) se mencionó como una manera de interactuar con Bot Service mediante el lenguaje natural. Para obtener más información, consulte Azure Language Understanding (https://www.luis.ai/).
- QnA Maker se mencionó como una solución de asistente virtual previamente empaquetado disponible en Azure Marketplace. Para obtener más información, consulte https://www.qnamaker.ai/.
