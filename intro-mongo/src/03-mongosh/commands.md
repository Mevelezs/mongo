## connect to container

```sh
docker-compose exec mongodb bash

```
## Connect with mongosh

```sh

mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://mauricio:admin123@cluster0.73ruman.mongodb.net/test"

```

```sh

show dbs
show collections

```

```sh

use('DB-Prueba');

db.Products.find()


```
