<img width="539" height="207" alt="image" src="https://github.com/user-attachments/assets/9dbe53d9-6cc4-4e16-b6ef-7bc15e361f46" />



# Clasificación No Supervisada, Semisupervisada y Supervisada para la Caracterización de Yacimientos No Convencionales
Este repositorio corresponde al proyecto final del Diplomado en Ciencia de Datos de la ENES-UNAM, Unidad León

Esta conformado por el archivo Datos.rar, que contitne:

    	datos_yacimiento.nc (datos originales y entrada del Notbook “Carga_Exploración_Limpieza_yacimiento.ipynb”)
    	datos_clean_yacimiento.nc (datos depurados, salida del Notbook “Carga_Exploración_Limpieza_yacimiento.ipynb” y entrada de los notbooks “CNS_yacimiento.ipynb”, “CS_yacimiento.ipynb” y “CS_CPA_yacimiento.ipynb”)
    	Well_6.cvs (Datos de 6 pozos con etiquetas de calidad del yacimiento)

los Notebook:

	Carga_Exploración_Limpieza_yacimiento.ipynb

    	Instalación e Importación de librerías
    
    	Funciones generadas para el análisis
    
    	Carga de Archivos SGY
    
    	Lectura de archivos SGY, y conversión a DataFrame con MultiIndex (inline, xline, samples)
    
    	Ordenar el Dataframe por Índices del DataFrame con MultiIndex
    
    	Reordenar encabezados
    
    	Conversión del DataFrame a un Xarray.Dataset
    
    	Despliegue de información en Slice, Inline y Xline, a partir del Dataframe ordenado por índices
    
    	Salvar Xarray.Dataset en formato NETCDF5
    
    	Lectura de Xarray.Dataset en formato NETCDF5
    
    	Exploración de Datos
    
    	Limpieza de datos y control de calidad
    
    	Salvar Datos limpios
    
    	Exportar Resultados

	CNS_yacimiento.ipynb

    	Instalación e Importación de librerías
    
    	Funciones generadas para el análisis
    
    	Cargar Datos limpios
    
    	Matriz de correlación
    
    	Componentes Principales
    
    	Cargas Factoriales
    
    	Método del Codo + Análisis de Silueta
    
    	Clasificación No Supervisada
    
    	Crear DataFrame PCA con clusters (índices sincronizados) y Firmas de Cluster
    
    	Revisión de la Clasificación no supervisada en el dominio original
    
    	Clasificación No supervisada con las variables representativas
    
    	Clasificación No supervisada con minmaxscaler
    
    	CNS con Transformación de datos
    
    	CNS con Transformación de datos 2
    
    	Exportar Resultados

	CS_yacimiento.ipynb

    	Instalación e Importación de librerías
    
    	Funciones generadas para el análisis
    
    	Carga de pozos
    
    	Carga de datos limpios
    
    	Clasificación No supervisada con las variables principales y la transformación 2
    
    	Estimación de Hiperparametros de los modelos de Clasificación Supervisada
    
    	Clasificación Supervisada con los parámetros más representativos y con la Transformación 2
    
    	Clasificación Semisupervisada
    
    	Exportar Resultados
    
    	Bibliografía

	CS_CPA_yacimiento.ipynb

    	Instalación e Importación de librerías
    
    	Funciones generadas para el análisis
    
    	Carga de pozos
    
    	Carga de datos limpios
    
    	Clasificación No supervisada con las variables principales y la transformación 2
    
    	Estimación de Hiperparametros de los modelos de Clasificación Supervisada
    
    	Clasificación Supervisada con los parámetros más representativos y con la Transformación 2
    
    	Clasificación Semisupervisada
    
    	Exportar Resultados
    
    	Bibliografía
