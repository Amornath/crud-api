#### Project Setup

In order to run this project, in the root create .env with these three variables, with your own values.

MONGO_URI in app.js file
JWT_SECRET in models/User.js file
JWT_LIFETIME in models/User.js file

After that run this command

```bash
npm install && npm start
```

#### API end-points

If you run this project in localhost then it will run on 5000 port. Also you can change this.

Authentication
POST http://localhost:5000/api/auth/register
POST http://localhost:5000/api/auth/login

CRUD
GET http://localhost:5000/api/items
GET http://localhost:5000/api/items/{id}
POST http://localhost:5000/api/items
PATCH http://localhost:5000/api/items/{id}
DELETE http://localhost:5000/api/items/{id}
