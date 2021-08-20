<h1>Digital Innovation - Developing a REST API people management system with Spring Boot</h1>

Development of a small system for managing people in a company through a REST API, created with Spring Boot.

The following were elaborated and standardized:

* Initial project setup with Spring Boot Initializer
* Creation of data model for mapping entities in databases
* Development of user management management (Registration, reading, updating and removing people from a system).
* Relation of each of the above operations with the REST architectural pattern, and an explanation of each of the REST concepts involved during project development.
* Development of unit tests for functionality validation
* Cloud system deployment through Heroku

To run the project without a terminal, type the following command:

```shell script
mvn spring-boot:run 
```

After executing the above command, just open the following address and view the project execution:

```
http://localhost:8080/api/v1/people
```


The following prerequisites are necessary for the execution of the project developed during the class:

* Java 11 or higher.
* Maven 3.6.3 or higher.

Deploy performed on Heroku.

Useful links:

* [Official Spring website](https://spring.io/)
* [Official Spring Initialzr site for project setup](https://start.spring.io/)
* [Heroku's official website](https://www.heroku.com/)
* [Official Lombok Documentation](https://projectlombok.org/)
* [Official Map Struct Documentation](https://mapstruct.org/)
* [Reference for the REST architectural standard](https://restfulapi.net/)


[On this link](https://drive.google.com/file/d/1crVPOVl6ok2HeYjh3fjQuGQn2lDZVHrn/view?usp=sharing), follow the slides presented as the script used for the development of the project.
