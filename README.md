Generador de Presentaciones Beamer con IA 📊🤖
Este proyecto automatiza la creación de diapositivas académicas en LaTeX Beamer a partir de archivos PDF. Utiliza la potencia de Google Gemini AI para resumir contenido y estructurarlo directamente en código LaTeX listo para compilar.

🌟 Características
Extracción Inteligente: Lee múltiples archivos PDF automáticamente usando PyMuPDF.

Resumen Académico: Procesa el texto con el modelo gemini-flash-lite para identificar puntos clave.

Formato Beamer: Genera entornos de frame, itemize y blocks (conceptos importantes).

Plantilla Personalizable: Permite insertar metadatos (Curso, Título, Autor) en una plantilla .tex predefinida.

🛠️ Instalación
Para ejecutar este script, necesitas instalar las siguientes dependencias en tu entorno (Local o Google Colab):

Bash
pip install --upgrade PyMuPDF google-generativeai
🚀 Uso Rápido
Configura tu API Key: Obtén tu clave en Google AI Studio e insértala en el script.

Prepara tus archivos: Coloca tus PDFs (ej. lectura_economia.pdf) y tu plantilla mi_plantilla.tex en la misma carpeta.

Ejecuta el script:

Python
python beamer_generator.py
Ingresa los datos: El script te pedirá el nombre del curso, título y autor para personalizar la portada.

📂 Estructura del Repositorio
beamer_generator.py: Script principal basado en funciones/clases.

mi_plantilla.tex: Archivo base de LaTeX con los marcadores {{TITULO}}, {{CONTENIDO}}, etc.

requirements.txt: Lista de librerías necesarias.

README.md: Documentación del proyecto.

🎓 Aplicación Académica
Este flujo está diseñado para estudiantes e investigadores que buscan optimizar su tiempo al crear material de exposición basado en papers, reportes del INEI o bases de datos económicas.

Desarrollado por: [Tu Nombre/Anjaly Arcos]

Organización: Mundo Social / UNMSM
