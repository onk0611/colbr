## Routing

# Registration user

https://www.exemple.com/api/register 

{
    "name": "your name",
    "email": "your@email.com",
    "password": "your_password"
}

scroll and get your access token

# Login user

https://www.exemple.com/api/login

{
    "email": "your@email.com",
    "password": "your_password"
}

scroll and get your access token

# Get user's information from access token

https://www.exemple.com/api/get-user

In postman : select Authorization Bearer and paste token
