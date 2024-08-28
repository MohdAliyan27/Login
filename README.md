Clone the Project and use 
1) Check for DB is connected
2) node server.js
3) Signup: Send a POST request to http://localhost:5000/api/auth/signup with a JSON body as:
{
  "username": "testuser",
  "password": "password123"
}
4) Now the testuser will be created SignUp process is completed.
5) Login: Send a POST request to http://localhost:5000/api/auth/login with a JSON body:
{
  "username": "testuser",
  "password": "password123"
}
6) Now we should receive a JWT token in response if the login is successful.
7) 
