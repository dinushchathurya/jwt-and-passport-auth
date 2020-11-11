# Passport JWT Auth

In here, I have created authentication with Passport and JWT (JSON Web Token). In this application, I have only implemented Twitter, LinkedIn and GitHub Authentications.

## Requirements

* Node.js

## Run this Application

To run this application, 

* clone this repository `git clone https://github.com/dinushchathurya/jwt-and-passport-auth` 

* Then `cd jwt-and-passport-auth`

* Run `npm install`

* Then run `nodemon app.js`

* Then you can test your API using application like postman 

## API Testing

### Signup

Method: POST <br>
URL:http://localhost:3000/signup <br>
Body <br>
x-www-form-urlencoded

| Key           | Value              |
| ------------- |:-------------:     |
| email         | example@example.com|
| password      | password           | 

### Login

Method: POST <br>
URL:http://localhost:3000/login <br>
Body <br>
x-www-form-urlencoded

| Key           | Value              |
| ------------- |:-------------:     |
| email         | example@example.com|
| password      | password           | 

### Profile

Method: GET <br>
URL:http://localhost:3000/user/profile <br>
Params

| Key         | Value         |
| ------------|:-------------:|
| secret_token| token         |


## Contact

For further more clarifications or regarding any issues, please contact me via my E-Mail.

## License

Copyright (c) 2020 <a href="https://dinushchathurya.github.io/">Dinush Chathurya</a> and <a href="https://codingtricks.io/">codingtricks.io</a>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Blog

https://codingtricks.io/

## 

<p ><h2 align="center">Happy<i class="fa fa-heart" style="color:red;"></i> Coding<i class="fa fa-code" style="color:orange;"> </i></h2></p>
