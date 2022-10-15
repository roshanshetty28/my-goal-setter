# Goal Setter

This purpose of this Web-application is to create, delete and view goals set by the user.

## Description

### About the Working of this application
This web-app has a Register page through which new users can register themselves to use this app. 
User is auto-logged in case the user has not logged out from the application in the last session.
Tasks set by the user are saved in text format.
Times Stamps are dispalyed on every task to help user track the goal created.
 
### About the dependencies

Frontend of this web-app is made using ReactJS, a popular frontend library of JavaScript. 
State of the application is maintained and updated using @reduxjs/toolkit. 
React-router-dom is used for routing. 
For the icons the application uses react-icons library. 
Errors are displayed using react-toastify. 
Axios is used to make HTTP request to the backend.

Backend of this website makes use of ExpressJS, framework of NodeJS.
The application makes uses of REST architecture.
JsonWebToken (JWT) is used to securely transfer data between frontend and backend of the app.
Bcrypt library is used to encrypt the sensitive user data for extra security.
The application makes use of cloud database MongoDB Atlas to store users and their goals information.
Express-async-handler library to efficiently make async calls.


## Getting Started

### Dependencies

* npm
* ReactJS
* NodeJS
* ExpressJS
* Nodemon
* react-router-dom
* reduxjs/toolkit
* react-redux
* react-icons
* react-toastify
* express-async-handler
* axios
* jsonwebtoken
* bcrypt
* concurrently
* MongoDb Atlas Account
* Postman Software
* Redux Dev Tools

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program

```npm 
npm run dev
/* to run the frontend and backend simultaneously*/
```

## Help

```
Common Issues and solutions:
* IP issue with MongoDB while starting the program
->Stop current execution. Go to MongoDB Atlas and add your current IP of your machine and run start the app again.
```

## Authors

Contributors names and contact info

Roshan Ravi Shetty  
[@RoshanShetty](https://wwww.linkedin.com/in/roshan-shetty-2000)

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

* [TraversyMedia](https://www.youtube.com/c/TraversyMedia)
