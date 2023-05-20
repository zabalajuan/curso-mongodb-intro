# connect to contaniner comando para entrar a la terminal del docker que tenemos corriendo
```sh
docker-compse exec mongodbbase bash
```
## connect with mongosh - usando la URL de conexion que da mongo
```sh
mongosh ""
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