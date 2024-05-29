# Prpactica de Cassandra Usando ASTRA-DATASTAX

En este ejemplo estaremos usando una interfaz de Astra-Datastax para poder probar, el funcionamiento de Cassandra, revisar un poco la sintaxis del lenguaje CQL.

Lo primero que hay que hacer es Ingresar a ASTRA-DATASTAX en el siguiente [LINK](https://astra.datastax.com/signup), en mi caso me registré con mi cuenta de gmail.

Una vez dentro tendrás acceso la consola de ASTRA, puedes explorar un poco por tu cuenta si deseas, en esa pantalla, puedes ir a inicio rápido y hacer click en "*Crear Base de Datos*" como se pmuestra en la imagen siguiente.

![Crear BD](Cassandra-Datastax/images/bienvenida-Astra.jpeg)

Luego saltará una pantalla emergente, allí elegiremos la configuración de arranque de nuestra BD, el nombre, el espacio de trabajo en nuestro caso ya las Queries están definidas para el nombre "*training*", luego a partir de allí, se procederá a elegír el proveedor de nube sobre el cual correra nuestra BD. Es recomendable hacerlo en el proveedor que tenga la ubicación mas próxima a donde será consultada. Al finalizar hacemos click en Crear BD.

![Configuración](Cassandra-Datastax/images/crear-bd-espacio-trabajo.jpeg)

Después de crear nuestra base de datos, se procederá a inicializar la instancia en la que correrá nuestra BD, cuando el estatus sea "*Active*", podemos ingresar a la cónsola de CQL para comenzar a correr nuestras consultas.

![Inicializado](Cassandra-Datastax/images/Inicializado-BD.jpeg)

![Consola-CQL](Cassandra-Datastax/images/consola-cql.jpeg)

Para correr las consultas pre-definidas de la práctica, recomiendo usar el archivo [trining.cql](Cassandra-Datastax\training.cql).

¡Disfruta-Juega-Prueba-Aprende! 😃
