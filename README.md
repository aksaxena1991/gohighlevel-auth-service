# Go High Level Auth Microservice 

This is a simple auth microservice built with Node.js, Express.js, MongoDB, and services are authorized with JSON Web Token (JWT).
Auth service is to suthenticate and authorize a user.

### Requirements
- Node.js and npm
- MongoDB

### Installation
- Clone repository
git clone https://github.com/aksaxena1991/gohighlevel-auth-service.git

- Install dependencies
cd gohighlevel-auth-service
npm install

- Create a [.env] file in the root directory of the project, and add the following environment variables:
PORT=3000
MONGODB_URI=mongodb://localhost:27017/authService
JWT_SECRET=goHighLevel

- Start server
npm run start

### Usage
- Login User
Navigate to http://localhost:3000/auth/loginUser.
Enter valid email and password.
Click the "Submit" button.
If the user is already there, then it will give you an error of already exist.

- Create User
Navigate to http://localhost:3001/auth/createUser.
Enter valid email and password.
Click the "Submit" button.

- Logout User

### Features
The customer wallet application has the following features:

- Create Wallet: Users can create their single wallet.
- Recharge Wallet: If wallet is already created then user can recharge the wallet.
