# node-mongo-login-signup-api

NodeJS + MongoDB API for User Management, Authentication and Registration

Step:1 git clone "https://github.com/oa07/node-signup-login-jwt/"
Step2 : cd node-signup-login-jwt
step 3: npm install
step 4 : npm start


# Postman Testing
Register: localhost:4000/users/register
                  Request Body: { "firstname" : "X ",
                                                 "lastname": "Y"  ,
                                                 "username": "ZZZZZ",
                                                 "password": "password"}

login:   localhost:4000/users/authenticate
                  Request Body: { 
                                                 "username": "ZZZZZ",
                                                 "password": "password"
                                                 }


