# PostmanTest
initial try of Postman

// see 3 responses generated in PostMan app through

1. POST - create New User
2. POST - LogIn 
3. GET  - get the info about the current User


// Details:

1. POST - create New User 
link: https://blog.kata.academy/api/users

body (raw - json) : 
{
  "user": {
    "username": "Albina",
    "email": "sirgalinaa@mail.ru",
    "password": "postman123"
  }
}


2. POST - LogIn 
link: https://blog.kata.academy/api/users/login

body (raw - json) : 
{
  "user": {
    "email": "sirgalinaa@mail.ru",
    "password": "postman123"
  }
}


3. GET  - get the info about the current User
link: https://blog.kata.academy/api/user
authorization >> Bearer Token >> token received in response from server at registration stage
