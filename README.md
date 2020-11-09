# Django Angular 10 CRUD Example – MySQL + Django Rest Framework Tutorial

Tutorial Link: [Django Angular 10 CRUD Example – MySQL + Django Rest Framework Tutorial](https://loizenai.com/angular-10-django-mysql-rest-crud-api-example/)

![Django Angular 10 CRUD Example – MySQL + Django Rest Framework Tutorial](https://loizenai.com/wp-content/uploads/2020/07/Django-Angular-10-CRUD-Example-%E2%80%93-Fullstack-Angular-10-Django-Rest-Framework-MySQL-Tutorial.png)

Django is a Python-based free and open-source web framework that follows the model-template-view architectural pattern. Angular is a TypeScript-based open-source web application framework led by the Angular Team at Google. In the tutorial, I introduce how to build a Angular Django CRUD RestAPIs Fullstack Project with POST/GET/PUT/DELETE requests using Django Rest Framework and MySQL database with step by step coding examples.

## Architecture – Angular Django CRUD Application

![Overall Architecture – Angular Django RestAPIs FullStack Integration](https://loizenai.com/wp-content/uploads/2020/07/Overall-Architecture-Angular-Django-RestAPIs-FullStack-Integration.png)

- We build the backend Python Django Application that provides RestAPIs for POST/GET/PUT/DELETE Customer entities and store them in MySQL/PostgreSQL database.
- We implement the Angular CRUD Application that uses Angular HTTPClient to interact (call/receive requests) with Django backend’s RestAPIs and display corresponding page views in Browser

## DJANGO APPLICATION WITH DJANGO REST FRAMEWORK + MYSQL

- Django Application interacts with MySQL/PostgreSQL database via Model layers.
- The Views are simply Python functions that take web requests and return web responses.
- URLs are used to mapping each request with the corresponding views.

![DJANGO APPLICATION WITH DJANGO REST FRAMEWORK + MYSQL](https://loizenai.com/wp-content/uploads/2020/07/Django-RestAPIs-Workflow-Architecture.png)

## Django Project Structure

![Django Project structure](https://loizenai.com/wp-content/uploads/2020/07/Django-Project-Structure.png)

The Django RestAPIs project includes 2 folders:

- djangoLoiZenAiRestAPIs is a main project folder
- customers is an application folder

## Angular Frontend Architecture

![Angular Frontend Architecture](https://loizenai.com/wp-content/uploads/2020/07/Angular-Application-Architecture.png)

Angular CRUD Application is designed with 3 main layers:

- Service Layer is used to define Angular Common Services and HttpClient Services to interact with RestAPIs
- Component Layer is used to define Angular Components to show views in Browser for interacting with Users
- Router Layer is used to route URLs mapping with the corresponding Angular Components

## Angular Project Structure

![https://loizenai.com/wp-content/uploads/2020/07/Angular-Project-Structure-1.png](https://loizenai.com/wp-content/uploads/2020/07/Angular-Project-Structure-1.png)

Angular CRUD Application defines 3 components, 2 services, 1 routers, and 2 data models:

– Components:

add-customer component is used to add a new customer to system
list-customer component is used to show all customers on view pages, delete a customer and update a customer
message component is used to define a view to show logging message on browser
– Services:

customer.service.ts defines POST/GET/PUT/DELETE HTTP requests to Django RestAPIs with the built-in Angular HttpClient.
message.service.ts defines an array storage to log all messages when Angular CRUD App running
– Router: app-routing.module.ts defines how to map a corresponding Angular component with an URL.

– Models:

customer.ts defines the main data model of our application.
message.ts defines the response data model between Django RestAPIs and Angular application.

## Goal

Here is a list of goals for Angular 10 Django CRUD Example with Django Rest Framework and MySQL database:

– Add a Customer Entities from Angular Client:

![Goal 1 – Add a Customer Entity](https://loizenai.com/wp-content/uploads/2020/07/Goal-1-Add-a-Customer-Entity.png)

– List All Customer’s entities:

![Goal 2 – List All Customer’s entities from Angular Client](https://loizenai.com/wp-content/uploads/2020/07/List-All-Customers-entities-from-Angular-Client.png)

– Details a Customer:

![Goal 3 – Angular shows details of a Customer entity](https://loizenai.com/wp-content/uploads/2020/07/Angular-shows-details-of-a-Customer-entity.png)

– Update a Customer:

![Goal 4 – Angular update a Customer Entity](https://loizenai.com/wp-content/uploads/2020/07/Angular-Client-Update-a-Customer-Entity.png)

– Delete a Customer:

![Delete a Customer](https://loizenai.com/wp-content/uploads/2020/07/Goal-5-Angular-Client-delete-a-Customer-entity.png)


Related posts:

- [Angular Nodejs Fullstack CRUD Application with MySQL/PostgreSQL](https://loizenai.com/angular-nodejs-fullstack-crud-application-with-mysql-postgresql-angular-10-9-8-httpclient-client-nodejs-express-sequelize-orm/)
- [Angular & Nodejs JWT Authentication fullstack Example](https://loizenai.com/angular-nodejs-jwt-authentication-examples-tutorials/)
- [Angular CRUD Application with SpringBoot and MySQL/PostgreSQL RestAPIs](https://loizenai.com/angular-crud-application-with-springboot-and-mysql-postgresql-restapis-fullstack-angular-httpclient-post-get-put-delete/)
- [Angular Spring Boot JWT Authentication Example](https://loizenai.com/angular-spring-boot-jwt-authentication-example-angular-6-8-9-spring-security-mysql-postgresql/)
