![Image description](public/img/logo.jpg)

------------------------------------------------------
               Candidate challenge Drivania                   
------------------------------------------------------

You are tasked with the creation of a very simple RESTful API, preferably using the PHP Symfony
framework and its ecosystem.

###### It ask:
The basics specs include:
- At the application level, the API should allow CRUD operations on a simplified RideServices
list.
- The API should include a mechanism to search a product by uuid, serviceLocator, or pickUp
or dropOff locations.
- A rideService can be created or updated using standard POST, PUT or PATCH methods.
- A rideService should contain at least:
uuid
  - pickup (name, latitude, longitude)
  - dropOff (name, latitude, longitude)
  - vehicleType (enum, “sedan”, “van”, “suv”)

How would you design such API? Think about endpoint definitions, schemas, response codes. You
can use a tool such Swagger for this purpose. Think about performance and referential integrity
when designing the relational database - if this is your preferred storage technology.

###### Docker:        
- The project consists of Docker, so if you run from terminal:
    - make start you will already have the docker container.

###### Resultado esperado:

Implement at least 2 RESTful methods from the definition above. Explain your choices and possible
improvements. As a guidance:
- Try to be as much SOLID and clean as possible
- Use Domain Driven Design approach for the building blocks of the application. 
- Test (some of) your code.
