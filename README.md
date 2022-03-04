# Local MongoDB Replica Set deployment with docker-compose

Local setup MongoDB server with replication set using docker-compose

The MongoDB database connector uses transactions to support nested writes.
We get errors if we try to actually write to a database that does not have replication.

### You have two solutions:

1. Use [MongoDB Atlas](https://www.mongodb.com/atlas/database). It is a free-service where we can create MongoDB cluster that supports replication.
2. Setup a local MongoDB server with replication


## Installation

Clone the project

```bash
  git clone git@github.com:AlaeddineMessadi/Mongodb-Replica-Set-docker-compose.git mongodb-replset
```

Go to the project directory

```bash
  cd mongodb-replset
```

Start the server

```bash
  ./start_db.sh
```


## Tech Stack

- Docker (docker-compose)
- YAML
- Bash

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
