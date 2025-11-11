🧭 Proyecto Vanguard – A/B Testing de Interfaz Digital
📌 Descripción General

Este proyecto forma parte del Módulo 2 del bootcamp de Data Analytics, donde aplicamos técnicas de limpieza, análisis exploratorio, métricas de desempeño, pruebas de hipótesis y visualización de datos para evaluar la efectividad de un rediseño digital en Vanguard, una empresa de gestión de inversiones con sede en EE. UU.

El objetivo principal es determinar si una nueva interfaz de usuario (UI) más moderna e intuitiva, junto con prompts contextuales, logra aumentar la tasa de finalización de procesos por parte de los clientes.
🧩 Estructura del Repositorio
Proyecto-Vanguard/
│
├── bruto/                  # Archivos primarios (datasets originales)
│   ├── df_final_demo.csv
│   ├── df_final_web_data_pt1.csv
│   ├── df_final_web_data_pt2.csv
│   └── df_final_experiment_clients.csv
│
├── limpio/                 # Archivos procesados y notebooks de análisis
│   ├── 01_EDA_Data_Cleaning.ipynb
│   ├── 02_Performance_Metrics.ipynb
│   ├── 03_Hypothesis_Testing.ipynb
│   ├── 04_Tableau_Visualizations.ipynb
│   ├── data_clean.csv
│   └── merged_dataset.csv
│
├── scripts/                # Funciones auxiliares en .py (si aplica)
│   └── utils.py
│
├── README.md               # Documentación principal del proyecto
├── requirements.txt        # Librerías necesarias para reproducir el entorno
└── tableau_dashboard.twbx  # Archivo de Tableau con las visualizaciones
🧠 Contexto del Proyecto

El equipo de Customer Experience (CX) de Vanguard realizó un experimento digital para medir si un rediseño de la interfaz y la adición de mensajes contextuales mejoraban la experiencia del cliente.

🔬 El experimento:

Periodo: 15 de marzo de 2017 – 20 de junio de 2017

Grupos:

Control: Interfaz tradicional de Vanguard

Test: Nueva interfaz con mejoras visuales y prompts

Objetivo: Analizar si la nueva UI incrementa la tasa de finalización de procesos y mejora la experiencia digital de los clientes.

🧰 Datasets
Dataset	Descripción
df_final_demo	Información demográfica de los clientes (edad, género, antigüedad, balance, etc.)
df_final_web_data_pt1 / pt2	Trazas digitales de la interacción online de los clientes
df_final_experiment_clients	Asignación de clientes a grupos de control o test
Principales columnas

client_id: ID único del cliente

variation: Grupo de experimento (control / test)

process_step: Etapa dentro del flujo digital

date_time: Fecha y hora del evento

clnt_tenure_yr / mnth: Antigüedad del cliente

clnt_age, gendr, num_accts, bal, calls_6_mnth, logons_6_mnth

📊 Metodología

El proyecto se desarrolló en varias fases siguiendo una estructura semanal:

🔹 Semana 5

EDA & Data Cleaning:

Exploración inicial de los datasets.

Limpieza, unificación y validación de las fuentes.

Análisis del comportamiento de los clientes.

Performance Metrics:

Definición y cálculo de KPIs clave (tasa de conversión, finalización, etc.).

Comparación entre grupos Control vs. Test.

Hypothesis Testing:

Pruebas de hipótesis sobre diferencias de tasas de finalización.

Evaluación de la efectividad del rediseño con significancia estadística.

🔹 Semana 6

Visualización (Tableau):

Creación de dashboards interactivos que muestren resultados segmentados.

Visualizaciones por edad, género, comportamiento y tasa de éxito.

Presentación Final:

Integración de resultados, conclusiones y recomendaciones.

Preparación de la exposición (10 minutos ante stakeholders).

📈 Herramientas y Tecnologías

Lenguaje: Python

Entorno: Jupyter Notebook

Bibliotecas: pandas, numpy, matplotlib, seaborn, scipy, statsmodels

Visualización: Tableau

Gestión del proyecto: Trello (Kanban Board)

Versionado: Git + GitHub

🚀 Resultados Esperados

Determinar si la nueva interfaz digital mejora significativamente la tasa de finalización de procesos.

Identificar segmentos de usuarios más beneficiados por el rediseño.

Evaluar la eficiencia y duración del experimento y proponer mejoras futuras.

Presentar dashboards interactivos y una presentación ejecutiva para la toma de decisiones.

📁 Entregables

Repositorio GitHub con:

Código funcional (notebooks + scripts)

Archivo README (este documento)

Dashboard Tableau

Slides de presentación online

🔗 Enlace a Tablero Kanban (Trello)

🔗 Slides de Presentación (Google Slides)

🧾 Autores

Proyecto realizado por:
[Tu Nombre] y [Nombre de tu compañero/a]
Bootcamp Data Analytics – Módulo 2

💡 Licencia

Este proyecto es de uso educativo y de libre distribución bajo la licencia MIT.
© 2025 – Proyecto Vanguard
