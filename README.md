# book_store_api
# Features
- Admin authentication and authorization
- Books management (Create, Read, Update, Delete)
- Authors management (Create, Read, Update, Delete)
- Middleware for protected routes
- Hashing and salting passwords


# Technologies Used
Node.js
Express.js
MongoDB
Mongoose
JSON Web Tokens (JWT)
Bcrypt.js
Skills


# Usage
- Install Mongo DB on your local machine or use Mongo DB Cloud -> [Go To MongoDB Website](https://www.mongodb.com)
- Create `images` folder in your project

## Environment Variables
Create `.env` file in the root of your project and add the following

```
MONGO_URI= your mongodb uri
PORT= 8000
NODE_ENV= development
JWT_SECRET_KEY= your jwt secret key
USER_EMAIL= your email service for sending email
USER_PASS= your email service password
```

## Install Dependencies
```
npm install
```

## Run
```
npm start
```

