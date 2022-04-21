---
layout: article
title: DynamoDB
permalink: /dynamo.html
sidebar:
  nav: layouts
---

## ¿Qué es DynamoDB?

DinamoDB es un servicio de base de datos no relacional (NoSQL) que está completamente administrado por Amazon Web Services (AWS). Es conocido principalmente por tener bajas latencias y su gran escalabilidad.

DinamoDB hace uso de un modelo de base de datos no relacional lo que permite almacenar y recuperar los datos en formatos que no sean tablas. El usuario hace uso de este modelo de base de datos a través de consultas GET y PUT, el funcionamiento es análogo a [elasticsearch](https://recuperacionaccesoinfo.es/els.html).

## Seguridad DynamoDB

La seguridad de DynamoDB está mas que garantizada ya que Amazon DynamoDB ofrece control de acceso detallado (FGAC) para que un administrador proteja los datos en una tabla.

FGAC se basa fundamentalmente en el servicio [AWS Identity and Access Management](https://www.techtarget.com/searchaws/definition/Amazon-Web-Services-AWS-Identity-and-Access-Management-IAM), que se encarga de administarr las credenciales y los permisos.

Además un administrador puede ver las métricas de uso de DynamoDB con [Amazon CloudWatch](https://www.techtarget.com/searchaws/definition/CloudWatch)


## DynamoDB vs MongoDB

## Elegir entre DinamoDB y MongoDB

Elegir la base de datos correcta no es una elección fácil. Depende de una multitud de factores:

- Requisitos del usuario
- Implementación
- Requisitos de almacenamiento
- Funcionalidad
- Otros factores

Incluso si comparamos MongoDB y DynamoDB, no podemos compararlos directamente ya que están destinados a diferentes casos de uso.

Por ejemplo, DynamoDB es un servicio de base de datos NoSQL administrado, mientras que MongoDB es un software de base de datos NoSQL. Por lo tanto, la comparación directa más cercana sería  MongoDB Atlas, una base de datos administrada que ofrecen MongoDB Inc y DynamoDB.

Si actualmente utiliza el ecosistema de AWS para implementar y administrar aplicaciones, DynamoDB ofrece lo mejor de:

- Compatibilidad
- Facilidad de uso
- Integración

Sin embargo, su principal desventaja  es que el proveedor bloquea al usuario sin la capacidad de modificar fácilmente el entorno de implementación.

Por otro lado, MongoDB Atlas permite a los usuarios usar cualquiera de los proveedores de nube admitidos para:

- Crear un clúster de base de datos MongoDB
- Migrar a una base de datos MongoDB local con una configuración mínima Mínimo

MongoDB Atlas proporciona una plataforma simple para aprovisionar y administrar MongoDB se agrupa en varias nubes, pero carece de la estrecha integración de un producto integrado como DynamoDB.

Como plataforma madura, MongoDB tiene la ventaja en su conjunto de funciones integradas para la gestión básica de conjuntos de datos  con aserciones de esquemas nativos, soporte para múltiples tipos de índices y más. Además, puede configurarlo para satisfacer la mayoría de las necesidades de la base de datos.

Consulte la documentación oficial de [MongoDB](https://www.mongodb.com/docs/) y [DynamoDB](https://docs.aws.amazon.com/dynamodb/index.html) como la base ideal para profundizar en cada base de datos.

## Enlaces de interés

[Recuperación y Acceso a la Información](https://recuperacionaccesoinfo.es/)

[Introducción a elasticsearch](https://recuperacionaccesoinfo.es/els.html)

[Azure HD Insgihts](https://recuperacionaccesoinfo.es/azure.html)

[Datalab](https://recuperacionaccesoinfo.es/datalab.html)

Documentación adicional sobre [Recuperación y acceso a la información](https://www.recuperacion-acceso-informacion.es/)
