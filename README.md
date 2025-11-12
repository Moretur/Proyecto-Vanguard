# Proyecto Vanguard – A/B Testing de Interfaz Digital
### Descripción General

Este proyecto forma parte del Bootcamp de Data Analytics, donde aplicamos técnicas de limpieza de datos, análisis exploratorio, definición de métricas, pruebas de hipótesis y visualización para evaluar la efectividad de un rediseño digital implementado por Vanguard, una empresa líder en gestión de inversiones con sede en EE. UU.

El objetivo principal es determinar si una nueva interfaz de usuario (UI), más moderna e intuitiva, acompañada de prompts contextuales, logra aumentar la tasa de finalización de procesos digitales por parte de los clientes.

### Estructura del Repositorio

El proyecto se encuentra organizado de la siguiente manera:

Csv Bruto/ → Contiene los datasets originales sin procesar, incluyendo:

df_final_demo.csv

df_final_experiment_clients.csv

df_final_web_data_pt_1.csv

df_final_web_data_pt_2.csv

Csv Limpio/ → Carpeta destinada a almacenar los datos limpios y transformados tras la etapa de preprocesamiento.

Notebooks/ → Carpeta que incluye los cuadernos principales del proyecto:

1.Limpieza y Análisis Final.ipynb: encargado de la limpieza, integración y validación de los datos.

2.Test de Hipótesis.ipynb: contiene el análisis exploratorio, cálculo de métricas y pruebas estadísticas A/B.

Gráficas → Carpeta que incluye las gráficas del proyecto

.gitignore → Define los archivos y carpetas que no deben incluirse en el control de versiones.

Proyecto Vanguard Presentación.pdf → presentación en formato PDF, que resume de forma visual los principales hallazgos, métricas y conclusiones del proyecto.
La presentación está diseñada para acompañar la exposición final del análisis ante el equipo de Vanguard, mostrando los resultados de manera clara, ejecutiva y basada en datos.

README.md → Documento actual, que describe la finalidad y estructura del proyecto.

## Los notebooks deben ejecutarse en el orden indicado para reproducir correctamente los resultados del análisis.

## Contexto del Proyecto

El equipo de Customer Experience (CX) de Vanguard llevó a cabo un experimento digital con el objetivo de evaluar si un rediseño de la interfaz y la implementación de mensajes contextuales podían mejorar la experiencia del cliente y la finalización de procesos.

## Detalles del experimento

Periodo: 15 de marzo de 2017 – 20 de junio de 2017

Grupos:

Control: Interfaz tradicional de Vanguard

Test: Nueva interfaz con mejoras visuales y prompts contextuales

Objetivo: Analizar si la nueva UI incrementa la tasa de finalización de procesos y mejora la experiencia digital.

## Datasets

### Datasets principales:

df_final_demo: información demográfica de los clientes (edad, género, antigüedad, balance, etc.).

df_final_web_data_pt_1 y df_final_web_data_pt_2: trazas digitales de la interacción online de los clientes.

df_final_experiment_clients: asignación de clientes a grupos de control o test.

Principales columnas:

client_id: identificador único del cliente

variation: grupo de experimento (control / test)

process_step: etapa dentro del flujo digital

date_time: fecha y hora del evento

clnt_tenure_yr / clnt_tenure_mnth: antigüedad del cliente

clnt_age, gendr, num_accts, bal, calls_6_mnth, logons_6_mnth

## Metodología

El proyecto se desarrolló siguiendo un enfoque estructurado en dos etapas principales:

🔹 Semana 1 — EDA & Data Cleaning

Exploración inicial de los datasets.

Limpieza, unificación y validación de las fuentes de datos.

Análisis descriptivo del comportamiento de los clientes.

Performance Metrics

Definición y cálculo de KPIs clave (tasa de conversión, finalización, etc.).

Comparación de resultados entre grupos Control y Test.

Hypothesis Testing

Aplicación de pruebas de hipótesis sobre diferencias de tasas de finalización.

Evaluación estadística de la efectividad del rediseño.

🔹 Semana 2 — Visualización y Presentación

Creación de dashboards interactivos en Tableau.

Visualización de resultados segmentados por edad, género y comportamiento.

Elaboración de una presentación ejecutiva con conclusiones y recomendaciones.

## Herramientas y Tecnologías

Lenguaje: Python

Entorno: Jupyter Notebook

Bibliotecas: pandas, numpy, matplotlib, seaborn, scipy, statsmodels

Visualización: Tableau

Gestión del proyecto: Trello (Kanban Board)

Versionado: Git + GitHub


## Resultados Esperados

Determinar si la nueva interfaz digital mejora significativamente la tasa de finalización.

Identificar segmentos de usuarios más beneficiados por el rediseño.

Evaluar la eficiencia y duración del experimento y proponer mejoras futuras.

Presentar dashboards interactivos y un informe ejecutivo para la toma de decisiones.

## Autores

Proyecto realizado por:

Andrés Moral

Adrián Rubio

Bootcamp de Data Analytics — 2025

## Licencia

Este proyecto es de uso educativo y de libre distribución bajo la licencia MIT.
© 2025 – Proyecto Vanguard
