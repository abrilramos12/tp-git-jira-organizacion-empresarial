# tp-git-jira-organizacion-empresarial
# Análisis de Ventas de una Pequeña Empresa

## Integrante

Abril Genoveva Ramos Dietmair

## Escenario elegido

Escenario B – Análisis de Ventas de una Pequeña Empresa.

El objetivo del proyecto es analizar un conjunto de datos de ventas comerciales para obtener información relevante sobre el desempeño de una empresa, utilizando herramientas de control de versiones y trabajo colaborativo mediante Git, GitHub y Jira.

## Descripción del Dataset

Se utilizó un archivo CSV denominado `ventas.csv`, que contiene información sobre las ventas realizadas por una empresa. Los datos incluyen:

* Fecha de venta.
* Producto vendido.
* Cantidad de unidades vendidas.
* Precio unitario.

Estos datos permiten calcular indicadores como ventas totales y producto más vendido.

## Cómo ejecutar el script

1. Clonar el repositorio desde GitHub.
2. Verificar que el archivo `ventas.csv` se encuentre dentro de la carpeta `datos`.
3. Abrir una terminal en la carpeta del proyecto.
4. Instalar las dependencias necesarias:

```bash
pip install pandas matplotlib
```

5. Ejecutar el script:

```bash
python scripts/analisis_datos.py
```

6. El programa procesará los datos y generará un gráfico en la carpeta `resultados`.

## Resultados obtenidos

A partir del análisis realizado se obtuvieron los siguientes resultados:

* Cálculo automático de las ventas totales.
* Identificación del producto con mayor cantidad de unidades vendidas.
* Generación de un gráfico de barras para visualizar las ventas por producto.
* Organización de los resultados dentro de la carpeta `resultados`.

El proyecto permitió aplicar conceptos de análisis de datos, control de versiones con Git, colaboración mediante GitHub y gestión de tareas utilizando Jira.
