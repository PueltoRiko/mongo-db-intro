## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root@localhost:27017/?tls=false"
mongosh "mongodb+srv://pueltoadmin:puelto9024@mongodb101.podvkcn.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("store")
db.products.find()
```