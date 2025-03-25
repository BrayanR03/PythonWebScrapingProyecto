# 🎬 Web Scraping de Películas con Selenium & Plotly  

Este proyecto realiza **web scraping** de información sobre películas, extrayendo datos como título, calificación, votos, año, clasificación y duración. Luego, se lleva a cabo un **proceso de Data Wrangling** y se generan **gráficos interactivos con Plotly**.  

## 📥 Instalación de Dependencias  

Antes de ejecutar el código, instala los paquetes necesarios:  

```bash
pip install selenium pandas plotly

📌 Configuración del ChromeDriver
Para que Selenium funcione, necesitas el ChromeDriver, que debe coincidir con la versión de tu navegador Chrome.

1. Verifica la versión de Chrome:

    Abre Chrome y ve a chrome://settings/help.

    Anota la versión (ejemplo: 120.0.6099.71).

2. Descarga el ChromeDriver correspondiente:

    Ve a https://sites.google.com/chromium.org/driver/.

    Descarga la versión que coincida con tu Chrome.
    
    Link Chome Driver para versiones mayores a 115: 
    https://googlechromelabs.github.io/chrome-for-testing/#stable (Utilicé esta)

3. Descomprime el archivo:

    En Windows: Usa un programa como WinRAR o 7-Zip.

    En macOS/Linux: Ejecuta en la terminal:
    unzip chromedriver-linux64.zip

4. Ubica el ChromeDriver en la carpeta correcta:

    Mueve el archivo descomprimido a la carpeta del proyecto (webscraping/chromedriver-win64/).

    Si prefieres, agrégalo al PATH del sistema para evitar rutas manuales.

📊 Visualización de Datos con Plotly
Después de la extracción, los datos se procesan y se generan gráficos interactivos, como:

📈 Tendencia de calificaciones por año (Gráfico de líneas)

📊 Distribución de duración de películas (Histograma)

🔴 Relación entre votos y calificación (Scatter plot)

📌 Clasificación de películas más común (Barras)

🎭 Comparación de duración media por clasificación (Boxplot)


🖥️ Cómo Ejecutar el Proyecto

1️⃣ Clona este repositorio:
git clone https://github.com/BrayanR03/PythonWebScrapingProyecto.git

2️⃣ Instala las dependencias necesarias:
pip install pandas selenium plotly

3️⃣ Sigue los pasos de chromedriver mencionados anteriormente

4️⃣ Abre Jupyter Notebook y explora las visualizaciones interactivas

📧 Autor: Brayan R. Neciosup-Bolaños
