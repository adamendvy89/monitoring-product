# Project Title

Price Monitor app 

# Feature

Monitoring fabelio product price and add comment to each product

# List API

| API  | HTTP | Purpose |
| ------------- | ------------ | ------------- |
| /product  | GET | get all products list  |
| /product/new | POST | add new product with product url  |
| /product/:id | GET | get product by product id  |
| /comment/new | POST | add new comment on specific product  |
| /comment/:productid | GET | get comments by product Id  |
| /comment/delete/:id | DELETE | delete comment |


### Environment
NodeJs <br>
ExpressJs <br>
Mongodb with ODM mongoose <br>
ReactJs

### Server Requirements
PHP 5.5+ and Guzzle 6+
OpenSSL PHP Extension
PDO PHP Extension
Mbstring PHP Extension
Tokenizer PHP Extension
XML PHP Extension
Ctype PHP Extension
JSON PHP Extension
BCMath PHP Extension


### Setup

**Backend** <br>
```
$ npm install
$ npm start 
```
Run on http://localhost:8000<br>


**Frontend**  <br>
```
$ npm run serve
```
Run on http://localhost:8080 /



### Dependencies 
Puppeteer  <br>
Cheerio  <br>
Node-cron <br>
Mongoose <br>

### Deployment

Deployed with Google app engine and Google cloud storage<br>
Link : https://


## Author

* **Adam Endvy** - ()
