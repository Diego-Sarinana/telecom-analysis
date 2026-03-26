# ConnectaTel Analysis

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel, una empresa de telecomunicaciones en Latinoamerica.

Se trabajó inicialmente con los datos de 3 datasets: plans.csv, usage.csv y users.csv que se combinaron para crear un solo dataframe nombrado user_profile. Éstos son los datos que incluía cada dataset y que se combinaron:

plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)

users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)

usage.csv → detalle del uso real de los servicios (llamadas y mensajes)


📂 Contenido del repositorio

Diego-Sarinana/telecom-analysis - Se llevó a cabo una exploración, limpieza y análisis llevando un proceso dividido en las siguientes etapas: 
1. Cargar y explorar
2. Identificación de problemas de calidad de datos
3. Limpieza básica de datos
4. Summary statistics de uso por usuario
5. Visualización de distribuciones (uso y clientes) y outliers
6. Segmentación de Clientes
7. Insight Ejecutivo para Stakeholders

▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](URL_DEL_NOTEBOOK_EN_GITHUB)

O:

1. Abre el archivo '.ipynb' en GitHub
2. Haz clic en Open in Colab
   
📘 Cómo reproducir el análisis:
1. Abre 'Diego-Sarinana/Project-ConnectaTel.ipynb'
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde /data/ o desde un enlace público (según corresponda)
   
🧠 Objetivo del análisis:
Construir un perfil estadístico de los clientes. 
Detectar comportamientos atípicos. 
Crear segmentos de clientes.
