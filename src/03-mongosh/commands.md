## Connect to container

```sh
docker-compose exec mongodbtest bash
```

## Connect with mongosh

```sh
mongosh "mongodb+srv://jesusavh:jwqstyac6@mongodb101.3eb3lda.mongodb.net/test"
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
```


```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.productos.find()
```
