# TP_modulo2_Programacion_analisis

Este trabajo práctico consiste en la construcción de un **dashboard interactivo** en Python utilizando **Plotly** y almacenando datos en 
Base de datos de **SQLite**.

## Acerca del Dataset:

El mismo fue obtenido de la página :

https://www.kaggle.com/datasets/codebynadiia/gdp-per-country-20202025/data   (Datos públicos)

El  archivo contiene  datos anuales del Producto Interno Bruto (PIB) de todos los países reconocidos, correspondientes al período 2020-2025. Se excluyen los territorios en disputa. El conjunto de datos se compila a partir de fuentes del FMI y es ideal para estudiar las tendencias económicas mundiales, pronosticar y analizar el crecimiento o la caída de las economías individuales durante este período.
Los datos del año 2025 son estimaciones y estarán disponibles el próximo año.

El Dataset se encuentra en la carpeta Data/20220-2025.csv  de este repositorio

## Contenido del repositorio:

tp_modulo2_Programacion_analisis/

├── data/2020-2025.csv  (Dataset base)

├── notebooks/tp_modulo2.ipynb # Notebook con el desarrollo

├── scripts/create_db.py (Script de creación de la base)

├── dashboard_integral.html (Dashboard exportado a HTML)

├── requirements.txt (Dependencias)

└── README.md (Documentación)


## Cómo utilizar el proyecto:

1. Clonar este repositorio    

   git clone https://github.com/lulysciacca2013/TP_modulo2_Programacion_analisis.git
   
   cd TP_modulo2_Programacion_analisis

3. Instalar dependencias

   pip install -r requirements.txt

4. Crear la base de datos en:

   python scripts/create_db.py

   (Opcional: en el repositorio en "db/dataset_2020_2025.db" está la base de datos creada, solamente habría que ponerla en la carpeta 
    content de la notebook que se corre en el colab)

5. Abrir el dashboard:

   - Desde Colab: abrir notebooks/tp_modulo2.ipynb
   - Desde navegador: abrir dashboard_integral.html

## DATOS DEL PROYECTO:

### Materia: Programación Avanzada en Ciencia de datos
### Profesor: JUAN CARLOS CIFUENTES DURAN
### Trabajo realizado por: LUCIA JOSEFINA SCIACCA
### Año: 2025




   
