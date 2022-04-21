---
layout: article
title: Cloud Datalab
permalink: /datalab.html
sidebar:
  nav: layouts
---

## Cloud Datalab y notebooks

Cloud Datalab usa cuadernos en lugar de archivos de texto que contienen código. El manual recopila código,  documentación escrita con markdown y los resultados de la ejecución del código (ya sea como texto, imágenes o HTML/JavaScript). Al igual que un editor de código o un IDE, un cuaderno lo ayuda a ejecutar código de forma interactiva e iterativa y muestra los resultados junto con el código. Además, cuando comparte cuadernos con otros miembros del equipo, puede incluir código, documentación en formato Markdown y resultados que incluyen gráficos interactivos para darles un contexto en el  que los archivos de código  Python o SQL no pueden proporcionar. 

Los cuadernos de Cloud Datalab se pueden almacenar en Google Cloud Source Repository, un repositorio de Git. Este repositorio de Git se clona en un disco persistente adjunto a la máquina virtual. Esta copia forma su espacio de trabajo, donde puede agregar, eliminar y editar archivos. Para compartir su trabajo con otros usuarios del repositorio, debe confirmar sus cambios en el cliente de Git para enviar los cambios desde su lugar de trabajo local al repositorio. Los cuadernos se guardan automáticamente en el disco de forma continua a lo largo del tiempo, pero los usuarios también pueden guardar sus cambios en cualquier momento. Si borra el disco repetidamente, puede perder los cuadernos que no se envían explícitamente al repositorio de Git. Por este motivo, recomendamos NO borrar el disco continuamente.

Cuando se abre un cuaderno, se inicia un  backend "kernel" para administrar las variables definidas en la sesión y ejecutar el código del cuaderno. Cuando el código que se ejecuta accede a los servicios de Google Cloud, como BigQuery o Google Machine Learning Engine, utiliza la cuenta de servicio disponible en la máquina virtual. Por lo tanto, la cuenta de servicio debe estar autorizada para acceder a los datos o solicitar el servicio. Haga clic en el ícono de usuario en la esquina superior derecha de un cuaderno de Cloud Datalab o en la página de la lista de cuadernos en el navegador (es posible que deba cambiar el tamaño de la ventana del navegador) para ver el nombre del proyecto en la nube y las cuentas de servicio. La máquina virtual utilizada para ejecutar Cloud Datalab es un recurso compartido al que pueden acceder todos los miembros asociados con el proyecto en la nube. Por lo tanto, no se recomienda utilizar credenciales personales en la nube para acceder a los datos.

## Situaciones de uso de Cloud Datalab

Estas son algunas ideas para comenzar en Cloud Datalab:

- Escriba consultas  SQL para explorar los datos de BigQuery. Importe los resultados en un DataFrame y muéstrelos como un histograma o un gráfico de líneas.
- Lea datos de un archivo CSV en Google Cloud Storage, luego insértelos en un DataFrame para procesar mediciones estadísticas, como la media, la desviación estándar y el cuantil, usando Python.
- Pruebe un modelo TensorFlow o scikitlearn para predecir resultados o clasificar datos.

## Bibliotecas incluidas

Estas son las bibliotecas que se incluyen en los notebooks de Cloud Datalab y que se pueden usar.

### Instaladas con Conda

>crcmod at version 1.7 
>dask at version 0.17.1
>dill at version 0.2.6
>future at version 0.16.0
>futures at version 3.2.0
>google-api-python-client at version 1.6.2
>httplib2 at version 0.10.3
>h5py at version 2.7.1
>ipykernel at version 4.8.2
>ipywidgets at version 7.2.1
>jinja2 at version 2.8
>jsonschema at version 2.6.0
>matplotlib at version 2.1.2
>mock at version 2.0.0
>nltk at version 3.2.1
>numpy at version 1.14.0
>oauth2client at version 2.2.0
>pandas-gbq at version 0.3.0
>pandas at version 0.22.0
>pandocfilters at version 1.4.2
>pillow at version 5.0.0
>pip at version 18.1
>plotly at version 1.12.5
>psutil at version 4.3.0
>pygments at version 2.1.3
>python-dateutil at version 2.5.0
>python-snappy at version 0.5.1
>pytz at version 2018.4
>pyzmq at version 17.1.0
>requests at version 2.18.4
>scikit-image at version 0.13.0
>scikit-learn at version 0.19.1
>scipy at version 1.0.0
>seaborn at version 0.7.0
>six at version 1.11.0
>statsmodels at version 0.8.0
>sympy at version 0.7.6.1
>tornado at version 4.5.1
>widgetsnbextension at version 3.2.1
>xgboost at version 0.6a2

### Instaladas con pip

>apache-airflow at version 1.9.0
>apache-beam[gcp] at version 2.7.0
>bs4 at version 0.0.1
>ggplot at version 0.6.8
>google-cloud-monitoring at version 0.28.0
>lime at version 0.1.1.23
>protobuf at version 3.5.2
>tensorflow at version 1.8.0

## Enlaces de interés

[Datalab medium](https://medium.com/google-cloud/tagged/datalab)

[Recuperación y Acceso a la Información](https://recuperacionaccesoinfo.es/)

[TensorFlow vs. Scikit-Learn: How Do They Compare?](https://analytics-proxy.springboard.com/blog/data-science/scikit-learn-vs-tensorflow/)

[Introducción a elasticsearch](https://recuperacionaccesoinfo.es/els.html)

[Azure HD Insgihts](https://recuperacionaccesoinfo.es/azure.html)

[DynamoDB](https://recuperacionaccesoinfo.es/els.html)

[Documentación adicional sobre Recuperación y acceso a la información](https://www.recuperacion-acceso-informacion.es/)
