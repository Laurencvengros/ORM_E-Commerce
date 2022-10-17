## ORM_E-Commerce

## Table-of-Contents

1. [Description](#description)

2. [User Story](#user-story)

3. [Installation](#installation)

4. [Usage](#usage)

5. [Application Demo](#application-demo)

6. [Technologies](#technologies)

7. [Links](#links)

8. [Contact Me](#contact-me)

    

## Description

A node.js application that uses and Express.js server, MySQL database and dotenv for a backend Ecommerce site. This application has RESTful APIs that have CRUD functiontions and uses sequelize as an ORM tool The application is back end only so insomnia is used to create requests to the API.




## User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```



## Installation 

* To run this application follow these steps:
    1. clone the repository using 
        * /git@github.com:Laurencvengros/ORM_E-Commerce.git\
    2. npm init --y
    3. npm install sequelize
    4. npm install mysql2
    5. npm install express

* open mysql2 by using: mysql -u root -p
    1. input source db/shcema.sql
    2. use ecommerce_db

* Exit mysql by running "quit", then enter:
    1. npm run seed
    2. npm start or node server.js
    


---


## Usage

* open mysql2 by using: mysql -u root -p and enter your password

    1. input source db/shcema.sql
    2. use ecommerce_db

* Exit mysql by running "quit", then enter:
    1. npm run seed
    2. npm start or node server.js

* open insomnia and enter localhost:3001 in the url
* You can enter GET, POST, PUT and DELETE requests for products, categories and tags to test your data in those routes. 



## Application Demo

* The videos below demonstrate the finctionality of the application in insomnia.

1. This Video test “GET ALL tags,” “GET ALL Categories,” and “GET All Products.”
[GET ALL Demo](./animations/GET%20all%20tags%2C%20products%20%26%20categories.webm "Demo of the GET ALL request")

2. This video tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”
[GET by ID Demo](/animations/GET%20by%20ID.webm "Demo of GET by ID")

3. This video tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”
[POST, PUT, DELETE Category Demo](./animations/POST%2C%20PUT%2C%20DELETE.webm "DELETE Category by ID,” “CREATE Category,” and “UPDATE Category")

4. This video tests the POST, PUT, and DELETE routes for products and tags.
[POST, PUT, DELETE products and tags Demo](./animations/POST%2C%20PUT%2C%20%20DEL%20tags%26products.webm "POST, PUT, DELETE tags and products")

## Technologies

* This application is created using:

    - Javascript
    - Node.js
    - Express.js
    - MySql2
    - Sequelize
    - dotEnv


## Links

* Link to GitHub Repository: https://github.com/Laurencvengros/ORM_E-Commerce.git


* Click the link to watch the demos:
 - GET ALL:  https://watch.screencastify.com/v/OfosyGvwkfPCegmx8h2A
    ![GET All](./animations/images/GET_ALL.jpg  "Screenshot of screencastidfy video  for GET ALL request" )
 
 - GET by ID: https://watch.screencastify.com/v/nL7FrG8gS4mGFKBhreZ6
    ![GET by ID](./animations/images/GET_byID.jpg  "Screenshot of screencastidfy video  for GET by ID request" )
 - POST, PUT, DELETE Categories: https://watch.screencastify.com/v/zCas5a5hTOvc6rYJBvLB
    ![POST, PUT, DELETE](./animations/images/POST_PUT_DELETE.jpg  "Screenshot of screencastidfy video  for POST, PUT, DELETE request" )
 
 - POST, PUT, DELETE Tags and Products: https://watch.screencastify.com/v/egFtS9ChsZ5ThwNzHl9B
     ![POST, PUT, DELETE Tags & Products](./animations/images/tagsandproducts.jpg "Screenshot of screencastidfy video  for POST, PUT, DELETE tags & products request" )






## Contact Me

* This Ecommerce application was developed by Lauren Cvengros

*  For questions, comments, concerns people contact me at l.cvengros@icloud.com


