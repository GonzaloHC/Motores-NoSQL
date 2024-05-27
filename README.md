# Motores-NoSQL
Revisemos algunos de los principales motores NoSQL, un muy breve paso por su historia, que lenguaje de consulta utiliza, algunas de las empresas que lo usan en sus proyectos y en algunos casos el uso de prácticas guiadas, para ver su funcionamiento. 

## Tabla de Contenido

- [DynamoDB](#dinamodb)
- [Hbase](#hbase)
- [Cassandra](#Cassandra)
- [Neo4j](#neo4j)
- [MongoDB](#mongodb)
  
## DynamoDB
### 📜Historia
Amazon lanzó DynamoDB en 2012 como una base de datos NoSQL completamente administrada que se integra bien con otros servicios de AWS.
### 📚 Características
DynamoDB es una base de datos NoSQL de clave-valor que ofrece escalabilidad, rendimiento y disponibilidad. Puede ser usada para migración de datos a la nube.
### 🔣 Lenguaje para consultas:
DynamoDB utiliza una API de bajo nivel para realizar consultas.
### 🎯 Ejemplo de empresas que lo usan
Disney Plus, usa Dinamo para almacenar las listas de series o películas del cliente. Zoom, Mercado libre, SAMSUNG, Netflix, Lyft, Tinder, Airbnb, Amazon.
### Herramientas Similares: Cloud Firestore Database, Redis, Microsoft Azure Cosmos DB.
### 📎 Enlace de interés
- [Amazon DynamoDB Customers | AWS](https://aws.amazon.com/es/dynamodb/customers/?pg=dynamodb&sec=cs#Zoom)

## HBASE
### 📜Historia
HBase se originó en 2007 como un proyecto de código abierto de Apache Hadoop.
### 📚 Características
HBase es una base de datos NoSQL de columnas amplias que se ejecuta en el clúster Hadoop. Utiliza como coordinador del cluster a Apache Zookeper. Se usa idealmente con datos que se escriben una vez y se leen muchas veces.
### 🔣 Lenguaje para consultas:
HBase utiliza una variante de SQL llamada Apache Phoenix. También se puede consultar desde Hive y SparkSQL pero estas últimas herramientas están menos optimizadas hacia Hbase.
### 🎯 Ejemplo de empresas usan HBase
Twitter, Yahoo y Facebook son algunos de los usuarios de HBase, que lo utilizan para almacenar y analizar grandes cantidades de datos no estructurados o semiestructurados.
### Herramientas Similares: 
Cassandra, Datastax, ScyllaDB, Google Cloud Bigtable, Accumulo, Elassandra.
### 📎 Enlaces de interés

- [Apache HBASE Base de Datos Hadoop BigData BigTable - Jose Bernalte](https://www.josebernalte.com/tool/hbase/)
- [Companies using Apache Hbase and its marketshare](https://enlyft.com/tech/products/apache-hbase)

## Cassandra
### 📜Historia
Facebook desarrolló Cassandra en 2008 y lo lanzó como un proyecto de código abierto en 2009 ⁷.
### 📚 Características
Cassandra es una base de datos NoSQL de columnas amplias que ofrece escalabilidad, disponibilidad y tolerancia a fallos. Sistema Pair to Pair. Se usa generalmente cuando la escritura de los datos supera la lectura.
### 🔣 Lenguaje para consultas:
Cassandra: Cassandra utiliza Cassandra Query Language (CQL), que es similar a SQL.
### 🎯 Ejemplo de empresas que usan Cassandra
Netflix, Spotify, Instagram y Reddit son algunos de los clientes de Cassandra, que lo utilizan para gestionar grandes volúmenes de datos distribuidos globalmente.
### 📎 Enlace de interés
[Cassandra ¿qué es y cuándo usarla? - Refactorizando](https://refactorizando.com/cassandra-que-es-cuando-usarla/)

## Neo4j
### 📜 Historia
Neo4j se lanzó en 2007 como una base de datos de gráficos de código abierto. 
### 📚 Características
Neo4j es una base de datos de gráficos que utiliza el modelo de datos de gráficos para almacenar y consultar datos
### 🔣 Lenguaje para consultas: 
Neo4j utiliza Cypher, un lenguaje de consulta de gráficos.
[***Práctica Guiada***](https://github.com/Ivan-Cepeda/Neo4J-Carga-Modelado-Consulta)

### 🎯 Ejemplo de empresas usan Neo4j
Walmart, eBay, NASA y LinkedIn son algunos de los clientes de Neo4j, que lo utilizan para modelar y explorar relaciones complejas entre datos.
### 📎 Enlace de interés
- [Qué es Neo4j y para qué sirve una base de datos orientada a grafos (bbva.com)](https://www.bbva.com/es/que-es-neo4j-y-para-que-sirve-una-base-de-datos-orientada-a-grafos/)
- [Companies using Neo4j and its marketshare (enlyft.com)](https://enlyft.com/tech/products/neo4j)

## MongoDB

### 📜 Historia
MongoDB se lanzó en 2009 como una base de datos de documentos de código abierto, La compañía creadora fue lanzada en 2007, por Dwight Merriman y Eliot Horowitz en 2007, su nombre viene de la palabra “humongous”, que significa enorme.
### 📚 Características
MongoDB es una base de datos de documentos que ofrece escalabilidad, flexibilidad y un modelo de consultas e indexación avanzado.
### 🔣 Lenguaje para consultas:
MongoDB utiliza un lenguaje de consulta basado en JSON llamado MongoDB Query Language (MQL).
### 🎯 Ejemplo de empresas usan MongoDB

Google, Adobe, Microsoft y Verizon son algunos de los clientes de MongoDB, que lo utilizan para desarrollar aplicaciones web y móviles innovadoras y escalables.

## Alternativas y Comparaciones entre distintos motores de Bases de Datos
Para comparar distintos motores de bases de datos, existe una página que lleva un ranking con todos ellos en general, y también los clasifica según su clasificación. Así mismo ofrece información individual respecto a cada una.

[DB-Engines Ranking - popularity ranking of database management systems]()


