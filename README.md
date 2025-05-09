Streamlit Split & Summarize
Descripción
Aplicación web desarrollada con Streamlit que permite dividir documentos PDF en segmentos más pequeños y generar resúmenes automáticos utilizando inteligencia artificial. Esta herramienta es especialmente útil para procesar documentos extensos que superan los límites de contexto de los modelos de IA.
Características

Carga de archivos PDF: Permite subir documentos PDF de cualquier tamaño.
Segmentación de texto: Divide el documento en segmentos más pequeños para un procesamiento eficiente.
Resumen automático: Genera resúmenes concisos de cada segmento utilizando modelos de IA.
Unificación: Consolida los resúmenes individuales en un resumen global coherente.
Interfaz amigable: Diseño intuitivo desarrollado con Streamlit.

Requisitos previos

Python 3.8+
Pip (gestor de paquetes de Python)
Cuenta en OpenAI o proveedor compatible de API de IA para la generación de resúmenes

Instalación

Clona el repositorio:

bashgit clone https://github.com/arklon1975/003-streamlit-split-summarize-v1.git
cd 003-streamlit-split-summarize-v1

Instala las dependencias:

bashpip install -r requirements.txt

Configura las variables de entorno (crea un archivo .env en el directorio raíz):

OPENAI_API_KEY=tu_clave_api_aquí
Uso

Ejecuta la aplicación Streamlit:

bashstreamlit run app.py

Abre tu navegador web en la dirección indicada (generalmente http://localhost:8501).
Sube un archivo PDF usando la interfaz de usuario.
Configura los parámetros de segmentación y resumen según tus necesidades.
Inicia el proceso y espera a que se genere el resumen final.

Estructura del proyecto
.
├── app.py                  # Aplicación principal de Streamlit
├── utils/
│   ├── pdf_processor.py    # Funciones para manejar archivos PDF
│   ├── text_splitter.py    # Lógica de segmentación de texto
│   └── summarizer.py       # Integración con API de IA para resúmenes
├── requirements.txt        # Dependencias del proyecto
├── .env                    # Archivo de variables de entorno (no incluido en git)
└── README.md               # Este archivo
Tecnologías utilizadas

Streamlit - Framework para aplicaciones web en Python
PyPDF2 - Biblioteca para manejo de PDFs
OpenAI API - Motor de IA para generación de resúmenes
Langchain - Framework para aplicaciones con LLMs

Colaboración
Las contribuciones son bienvenidas. Por favor, sigue estos pasos:

Haz fork del repositorio
Crea una rama para tu funcionalidad (git checkout -b feature/amazing-feature)
Haz commit de tus cambios (git commit -m 'Add some amazing feature')
Haz push a la rama (git push origin feature/amazing-feature)
Abre un Pull Request

Licencia
Este proyecto está licenciado bajo MIT License.
Contacto
Proyecto creado por arklon1975
