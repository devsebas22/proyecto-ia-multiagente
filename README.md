<p align="center">
  <img src="https://svg-banners.vercel.app/api?type=origin&text=Proyecto%20IA%20Multiagente&width=1000&height=200" alt="Banner">
</p>

📘 Proyecto Final – Introducción a la Inteligencia Artificial
Sistema Multiagente con Embeddings, Base Vectorial y Recuperación de Información (Mini-RAG)

Este proyecto implementa un asistente inteligente multiagente capaz de:

Extraer texto de documentos (TXT, PDF o imágenes con OCR)

Dividir el contenido en chunks

Generar embeddings semánticos

Guardarlos en una base de datos vectorial simple

Recuperar información mediante similitud (coseno / euclidiana)

Coordinar agentes usando LangChain

Producir respuestas en lenguaje natural basadas en los documentos cargados

Este trabajo corresponde al Proyecto Final del curso Introducción a la IA.

👨‍🏫 Autores

Juan Esteban Aguirre

Sebastián Mogollón

🚀 Tecnologías utilizadas

Python 3.10+

LangChain

FAISS o listas en memoria

OCR (Tesseract) opcional

OpenAI o HuggingFace Embeddings

NumPy / Pandas

Streamlit (interfaz)

PyPDF2 para PDF

Pillow para manejo de imágenes

📦 Instalación

Clona el repositorio:

git clone https://github.com/devsebas22/proyecto-ia-multiagente.git
cd proyecto-ia-multiagente


Instala dependencias:

pip install -r requirements.txt

▶️ Ejecución del proyecto
streamlit run src/app.py


Esto abrirá una interfaz donde puedes:

Subir documentos

Procesarlos

Consultarlos con lenguaje natural

Ver los fragmentos recuperados más relevantes

🧠 Arquitectura del sistema (Multiagente)

El proyecto utiliza tres agentes principales:

🔹 1. Agente de Extracción

Lee archivos

Realiza OCR si se requiere

Devuelve texto limpio

🔹 2. Agente de Análisis

Realiza chunking

Genera embeddings

Inserta vectores en la base

Recupera los fragmentos más similares

🔹 3. Agente de Respuesta

Recibe los fragmentos recuperados

Produce una respuesta clara y contextualizada

📂 Estructura del repositorio
proyecto-ia-multiagente/
│── data/
│   ├── ejemplos/
│   └── resultados/
│
│── src/
│   ├── agentes/
│   │   ├── agente_extraccion.py
│   │   ├── agente_analisis.py
│   │   └── agente_respuesta.py
│   ├── app.py
│   ├── chunking.py
│   ├── extraccion.py
│   ├── embeddings.py
│   ├── similitud.py
│   ├── vectores.py
│   ├── utils.py
│
│── docs/
│   └── Documento_Tecnico.md
│
│── requirements.txt
│── README.md

📝 Documento Técnico

El documento técnico completo está en:

docs/Documento_Tecnico.md


Incluye:

Introducción

Problema a resolver

Metodología

Arquitectura

Resultados

Trabajo futuro

📌 Notas finales

Este proyecto es un prototipo educativo, diseñado para demostrar la implementación práctica de un sistema RAG (Retrieval Augmented Generation) usando herramientas modernas, manteniendo claridad y modularidad.

📬 Contacto

Si deseas colaborar o reportar errores:
👉 Crea un Issue en este repositorio.
