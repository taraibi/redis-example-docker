# Holy Grail App 

A full stack holy grail using Redis as a database from Node.js

# Objective

Implement the data() method to use Promises to get the values, using the Redis client.
Implement the /update/:key/:value enpoint by using the Redis client to update a given key-value pair.


# How to Use
- `docker run -d --name <CONTAINER_NAME> -p 127.0.0.1:6379:6379 redis` create docker container
- make sure docker container is running
- open docker cli, `redis-cli` -> can list keys via `Keys *` then grab and check the value
- ```npm install```
- `node index.js` run on `http://localhost:3000`.


## License

[MIT](https://github.com/anyapages/holy-grail-app/blob/main/LICENSE) 
