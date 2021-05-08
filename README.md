# MERN_Authentication
A local authentication system Using a React/Node/Express/MongoDB stack.

# To make it work
You need to change the mongoDB URL (in server.js) to your own, with your database username and password included.

# To-Dos / Improvements
- Add an option to reset password (e.g. through nodemailer maybe)
- Add a confirmation email before adding the user to the DB when registering
- Only show a logout button if there is a flag indicating a user is logged in

# To start frontend
```bash
cd frontend
npm start
```

# To start backend (with nodemon)
```bash
cd backend
npm start
```

# Description

I was working on authentication for another project, and decided it would be helpful to encapsulate this authentication stack into a little package for learning purposes.


# The stack
```bash
React (frontend)
Node/Express (backend)
MongoDB (database)
```

# Frontend Dependencies
```bash
npm install react-router-dom (for making react router work)
```
```bash
npm install axios (for exchanging HTTP requests between frontend and backend)
```

# Backend Dependencies
```bash
npm install bcryptjs (for encrypting registering users' passwords)
```
```bash
npm install cookie-parser (for parsing cookies)
```
```bash
npm install cors (cross origin resource sharing)
```
```bash
npm install express (our backend server uses express, which is built on top of node.js)
```
```bash
npm install express-session (to allow for users to have a session once logged in)
```
```bash
npm install mongoose (mongoose is an ODM that makes writing schemas for MongoDB extremely easy)
```
```bash
npm install passport (passport deals with strategies for authenticating users making POST requests from the login page)
```
```bash
npm install passport-local (deals with local strategy for authentication (i.e. using a local username and password))
```