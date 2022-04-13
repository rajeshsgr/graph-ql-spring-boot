# graph-ql-spring-boot
This project lets you understand , how to implement GraphQl in SpringBoot Services.
It has a employee class and a address class, address is mapped to employee.
The data is being fetched from H2 db.

# graph-ql-spring-boot
Demo Service for graph QL
To run the example type - `mvn spring-boot:run` on console

To access the service, use POSTMAN
  
  POST http://localhost:8080/getemp
  
  POST Body Options
  ______________________
  
  ```{
    allEmployee
    {
          name
          
          age
          
          id
          
  }
  
  }
_____________________

{
  allEmployee{
    address {
              country
                city
                flat
                addid
  }
  }
  }
_________________________
