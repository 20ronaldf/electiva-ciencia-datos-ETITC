# electiva-ciencia-datos-ETITC

Análisis de Datos E-commerce
Este proyecto realiza un análisis exploratorio de datos de e-commerce, incluyendo visualizaciones interactivas y estáticas para comprender patrones de ventas y comportamiento de clientes.
🚀 Características

Análisis exploratorio de datos de e-commerce
Visualizaciones estáticas con Matplotlib y Seaborn
Gráficos interactivos usando Plotly y Bokeh
Filtrado de datos para análisis específicos
Estadísticas descriptivas del conjunto de datos

📋 Requisitos Previos

Python 3.8 o superior
Visual Studio Code
Extensión de Python para VS Code
Jupyter Notebook
pip (gestor de paquetes de Python)
Git

🔧 Instalación y Configuración

Clonar el repositorio:

bashCopygit clone https://github.com/20ronaldf/electiva-ciencia-datos-ETITC.git
cd ecommerce-analysis

Configurar el entorno virtual en Visual Studio Code:

bashCopy# Abrir el proyecto en VS Code
code .

# Abrir la terminal en VS Code (Ctrl+Shift+`)
python -m venv venv

# Activar el entorno virtual:
# En Windows:
.\venv\Scripts\activate

# Crear kernel para Jupyter
python -m ipykernel install --user --name=ecommerce_analysis

📊 Ejemplos de Visualizaciones
El proyecto genera varios tipos de visualizaciones:

Gráfico de barras de ventas por país
Histograma de cantidad de productos vendidos
Gráfico de dispersión interactivo con Plotly
Gráfico de líneas temporal con Bokeh

📝 Lista de Tareas

 Configuración del entorno virtual en VS Code
 Configuración de Jupyter Notebook con el entorno virtual
 Carga de datos desde URL pública
 Análisis exploratorio inicial
 Visualizaciones estáticas (Matplotlib/Seaborn)
 Visualizaciones interactivas (Plotly/Bokeh)
 Documentación del proyecto

🛠️ Construido Con

Visual Studio Code - Editor de código
Jupyter Notebook - Entorno de desarrollo interactivo
Python - Lenguaje de programación principal
Pandas - Análisis de datos
Matplotlib - Visualizaciones estáticas
Seaborn - Visualizaciones estadísticas
Plotly - Gráficos interactivos
Bokeh - Visualizaciones interactivas

⚙️ Dependencias Principales
Las dependencias principales se encuentran en requirements.txt:
Copypandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
plotly>=5.1.0
bokeh>=2.4.0
ipykernel>=6.0.0
jupyter>=1.0.0

✒️ Autores

Ronald Fernando Villail Villamil - Documentación

🎁 Agradecimientos

Dataset público de e-commerce utilizado en este análisis
Comunidad de Python por las excelentes librerías de visualización