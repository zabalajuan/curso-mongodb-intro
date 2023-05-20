# connect to contaniner comando para entrar a la terminal del docker que tenemos corriendo
```sh
docker-compse exec mongodbbase bash
```
## connect with mongosh - usando la URL de conexion que da mongo
```sh
mongosh ""
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://vantadb101:Zabala3024@mongodb101.kwzn3hq.mongodb.net/test"
```

## show databases 
```sh
show dbs
show collections
```

## run other commands 
```sh
use("platzi_store")
db.productos.find()
```

## exit database
```sh
.exit
```