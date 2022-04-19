---
title: Modelos de recuperación y acceso a la información
tags: TeXt
---

Se detallan en el presente artículo los modelos más utilizados en la Recuperación y Acesso a la Información, que son comúnmente denominados "modelos clásicos":

**- Modelo booleano:** En este modelo de Recuperación y Acceso a la Información cada documento tiene asociada una variable booleana por cada término de búsqueda. El valor de esta variable será 1 si el término de búsqueda aparece en el documento o 0 si no aparece. Por tanto, cada documento se De esta manera surgen una serie de operadores lógicos que posibilitan la creación de reglas relacionadas con la presencia de uno o varios términos en un documento seleccionado. Estos operadores son:
**-OR:**t1 OR t2 indica que se seleccionen los documentos que tengan presente, ó bien t1, ó bien t2.

**-AND:** t1 AND t2 indica que se seleccionen los documentos que tengan presente tanto t1 como t2.

**-NOT:** NOT t1 indica que se seleccionen aquellos documentos donde NO esté presente el término t1.

**-Modelo probabilístico:** En este modelo, nuevamente, cada documento tiene asociado "n" variables booleanas, donde "n" es el número de términos. Además, en este modelo, una consulta "Q" se representa por una serie de unos y ceros, donde los unos corresponden a los términos que deseamos hallar con la consulta. Para el proceso de acceso y recuperación de la información se siguen los siguientes procesos:
**-Cálculo de coef. iniciales:** se pretende, en este paso, conocer el estado de recuperación de cada uno de los términos.
**-Cálculo de la similitud entre cada documento y la consulta:** se realiza mediante la suma de los coeficientes iniciales correspondientes a los términos que están presentes tanto en el documento como en la consulta.

**-Modelo vectorial:** Este modelo de recuperación y acceso a la información representa cada documento de la colección como una agrupación de números reales positivos, a diferencia de los dos modelos anteriores, donde esos números únicamente podían tomar dos valores (término presente en documento o término no presente). Esta agrupación de números indica la relevancia de cada término en cada documento. Esto se traduce en una mayor precisión a la hora de recuperar la información.

Se utilizan dos criterios a la hora de dar un valor para cada término en cada documento:
    **-Term Frequency (tf):**frecuencia de aparición de término en el documento.
    
    **-Inverse Document Frequency:**: inverso del número de documentos en los que aparece el término. Este es un indicador, por tanto, de cómo de específico es un término en cada uno de los documentos.

<!--more-->
