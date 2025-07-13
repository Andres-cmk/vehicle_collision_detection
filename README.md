## 👁️🤖🧠 Sistema de Detección de Colisiones Vehiculares por Visión de Computadora 🚗
Hecho por: Andres Felipe Ramirez Montaña - andramirezm@unal.edu.co

## ¿Por que hacer esto? 
Los accidentes de tránsito representan una de las principales causas de muerte y
congestión en las vías urbanas. La detección manual de choques a través de cámaras de
vigilancia es ineficiente, ya que depende de la observación constante por parte del personal.
Esto retrasa la respuesta ante emergencias y dificulta la generación de reportes confiables.
Es necesario un sistema automatizado que identifique colisiones de forma oportuna y
documente los incidentes sin intervención humana. 

En los últimos años, las técnicas de aprendizaje profundo han mejorado notablemente la visión por computadora hasta un nivel que casi alcanza las capacidades humanas en la percepción visual. Por lo tanto, no es sorprendente que los sistemas modernos de advertencia de colisión hayan adoptado técnicas de visión por computadora basadas en aprendizaje profundo.

Para esto se van a utilizar las siguientes herramientas: 
- 👁️‍🗨️🧠 YOLO en su versión 11.
- Python 3 🐍.
- 💻☁️ Google Colab — Entrenamiento y pruebas en la nube.
- 🤖🖼️ Roboflow - Gestión y anotación de datasets.
- 👁️🛠️ OpenCV — Procesamiento de imágenes y video.

--- 
## Descripción del objetivo del proyecto 📄✏️

Este sistema inteligente integra modelos preentrenados de YOLO **(You Only Look Once)**, los cuales han sido adaptados y refinados mediante entrenamiento adicional utilizando datasets especializados en accidentes de tráfico.

El conjunto de datos fue cuidadosamente seleccionado para asegurar una alta calidad en la detección y clasificación de objetos relevantes en escenas viales, permitiendo no solo la identificación de vehículos, sino también de otros elementos presentes en el entorno, como peatones, señales de tránsito, motocicletas, escombros u objetos atípicos.

Esta capacidad mejora la precisión del sistema en situaciones reales, incluyendo aquellas donde se presentan colisiones, comportamientos anómalos o la presencia de objetos que no pertenecen al contexto vial. Con esto, el modelo no solo detecta, sino que comprende mejor el escenario del accidente, lo que es clave para sistemas de vigilancia, análisis forense y asistencia en tiempo real.

--- 
## Flujo del programa 📥
<img width="1047" height="460" alt="image" src="https://github.com/user-attachments/assets/06753ea0-cbab-4976-b6a9-b0b9a1a50d9e" />

Para mas información y el estudio que se realizo, se encuentra en el siguiente documento: ![aqui](https://github.com/Andres-cmk/vehicle_collision_detection/tree/main/Documentacion)


