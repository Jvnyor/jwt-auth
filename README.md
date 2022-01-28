# JWT Authentication with Spring Boot

## Path's:

/home - home page

/users - "list" of all users (requires token) (Postman recommended) - GET

#### Request to /login

```
{
  "username":"admin",
  "password":"password"
}
```

/login - return token in headers (Postman recommended) - POST
