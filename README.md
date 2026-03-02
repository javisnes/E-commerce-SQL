# 🛒 Análisis de Ventas E-commerce con SQL y Python

## 🎯 Objetivo del Proyecto
Demostrar el dominio de bases de datos relacionales y consultas estructuradas (SQL) simulando un entorno de negocio real. 
El proyecto responde a preguntas clave de negocio uniendo múltiples fuentes de datos.

## 🛠️ Tecnologías Utilizadas
* **SQLite:** Creación de base de datos relacional y ejecución de consultas.
* **Python (Pandas):** Procesamiento de resultados SQL a DataFrames para análisis visual.
* **Google Colab:** Entorno de desarrollo interactivo.

## 📂 Arquitectura de Datos
Se diseñó una base de datos con 3 tablas principales (Normalización):
1. `Clientes`: Información demográfica y nivel de suscripción.
2. `Productos`: Catálogo con categorías y precios.
3. `Ventas`: Registros transaccionales (Tickets).

## 🔍 Consultas Realizadas y Hallazgos
* **Uniones Complejas (INNER JOIN):** Cruce del registro de ventas con el catálogo de productos para reconstruir el historial financiero.
* **Agrupación y Agregación (GROUP BY / SUM):** Identificación de las categorías de productos más rentables, destacando **Hogar** como la principal fuente de ingresos.
* **Análisis de Clientes VIP (Múltiples JOINs):** Rastreo de los 5 clientes con mayor volumen de compra cruzando información de 3 tablas simultáneamente, identificando a **Argentina** como el país del cliente top.

## 💡 Impacto para el Negocio
Estas consultas permiten a la gerencia dirigir campañas de marketing de forma más efectiva, enfocándose en las categorías que generan más ingresos y fidelizando a los clientes VIP detectados por la base de datos.
