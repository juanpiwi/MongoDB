## Crear DB y Colecciones

* use <nombre-db> (crear DB)
* db (DB actual)
* show dbs (Todas la DB)

## Tamaño (bytes)

* db.collection.stats(tamaño)

* db.collection.dataSize(): el tamaño de los datos en la colección

* db.collection.storageSize(): la reserve de espacio incluido el espacio no utlizado

* db.collection.totalSize(): El tamaño de los datos más el de los índices

* db.collection.totalIndexSize(): el tamaño de los índices