# node-skylab
API REST using NodeJs and MongoDb, a project created in a rocketseat course.

## Development setup
install at the following dependencies:
- NodeJs with Npm manager
- Docker with MongoDb container

Starting the server and container MongoDb
1) Start MongoDb (`docker start <name of container>`)
1) Set the MongoDb path on server.js
1) Start the server on project path (`npm run dev`)

## NodeJs dependencies used in project
```js
  "dependencies": {
    "cors": "^2.8.5",
    "express": "^4.17.1",
    "mongoose": "^5.7.8",
    "mongoose-paginate": "^5.0.3",
    "require-dir": "^1.2.0"
  },
  "devDependencies": {
    "nodemon": "^1.19.4"
  }
```

## API Routes
- Get all: http://localhost:3013/api/products
- Get one: http://localhost:3013/api/products/<Product_Id>
- Post: http://localhost:3013/api/products with body req JSON
- Put: http://localhost:3013/api/products/<Product_Id> with body req JSON
- Delete: http://localhost:3013/api/products/<Product_Id>

## Course details
Free 14 lessons course offered by Rocketseat

https://skylab.rocketseat.com.br/journey/starter
