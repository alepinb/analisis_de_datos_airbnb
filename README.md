﻿# Proyecto Data Analysis - Airbnb Datasets 🏠

## Objetivo del Proyecto

El proyecto tiene como objetivo principal analizar los datos de Airbnb para identificar oportunidades de mercado y mejorar la estrategia de marketing. Se busca entender las tendencias de ocupación, precios y reseñas de los usuarios en diferentes ciudades. La visualización de estos datos en Microsoft Power BI permitirá a los equipos de marketing tomar decisiones basadas en datos para optimizar las campañas y mejorar la experiencia del usuario.

## Nuestra solución - El Dashboard PowerBI para Airbnb

- Un dashboard interactivo y visualmente atractivo, desarrollado para convertir los datos brutos en insights procesables.

![Dashboard PowerBI](airbnb6.png)

- Simplificamos la visualización de datos complejos para optimizar la toma de decisiones.


## Estructura del Proyecto

```
├── Dashboard_prop_regulares/
│   └── df_regular_definitivo.pbix: Archivo de Power BI con el dashboard final.
├── data/
│   ├── data_limpia/: Carpeta con los datos limpios.
│   └── Varios archivos CSV y Excel con los datos originales y transformados.
├── datasets_concat_eda.ipynb: Notebook con el análisis exploratorio de datos y concatenación de datasets.
├── eda_london.ipynb: Notebook con el análisis exploratorio de datos específico para Londres.
└── README.md: Este archivo.
```

## Instrucciones para Crear el Entorno de Trabajo

### 1. Clonar el Repositorio

```sh
git clone https://github.com/tu_usuario/airbnb_grupo1.git
cd airbnb_grupo1
````

### 2. Crear y Activar el Entorno Virtual
En Windows:
```sh
python -m venv venv
venv\Scripts\activate
```

En macOS y Linux:
```sh
python3 -m venv venv
source venv/bin/activate
```

### 3. Instalar las Dependencias
```sh
pip install -r requirements.txt
```

### 4. Ejecutar los Archivos .py y Notebooks

Para ejecutar los notebooks, puedes usar Jupyter:
```sh
jupyter notebook
```
Abre `datasets_concat_eda.ipynb` o `eda_london.ipynb` desde el navegador para explorar el análisis de datos.

### 5. Visualizar los Archivos de Power BI

Para visualizar los archivos `.pbix` en la carpeta `Dashboard_prop_regulares/`, sigue estos pasos:

1. Asegúrate de tener instalado [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Abre Microsoft Power BI Desktop.
3. Navega a `Archivo > Abrir` y selecciona `df_regular_definitivo.pbix`.


#### Importar Datasets en Power BI

Para que el dashboard sea completamente funcional, es necesario importar los datasets de las diferentes ciudades en Power BI. Sigue estos pasos para importar los datos:

1. Abre Microsoft Power BI Desktop.
2. Navega a `Inicio > Obtener datos`.
3. Selecciona el tipo de archivo que deseas importar (por ejemplo, CSV, Excel).
4. Busca y selecciona los archivos de datos en la carpeta `data/data_limpia/`.
5. Haz clic en `Cargar` para importar los datos en Power BI.

Una vez importados, asegúrate de que las relaciones entre las tablas estén correctamente configuradas para reflejar las conexiones entre los diferentes datasets.

Esto te permitirá explorar los dashboards y visualizaciones creadas a partir de los datos analizados.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para discutir cualquier cambio que desees realizar.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
