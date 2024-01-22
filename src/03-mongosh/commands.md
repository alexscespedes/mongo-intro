## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb+srv://alexandersenc99:fitness32@mongodb101.c5brgg1.mongodb.net/"
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```
