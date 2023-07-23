
# HOTEL-MANAGEMENT-JAVA
Creating HotelManagement system using java spring boot 
Where User can see how many numbers are in hotel and how many vacant. 
Hotel Has following properties
* Each Room has a Id
* Each Room has Type associated with it
* Each Room has a Price
* Each Room has a Status

  #### our project is having following endpoints
   * addRoom 
   * getAllRooms
   * getStatusOfRoom

## Frameworks and languages used
* Spring
* java
* Hibernate-validation
* Regex for validating patterns
* H2 Database

## Data Flow
 * Controller
       ** It is just containg Api endPoint and logic for 
           what should this api do.
* Services
      ** It has actual logic(business logic) for method. 
          It is also called Model.
       
 * Repository
        ** It is having data source

 ## Data Structure
   * Here we are using List(ArrayList) datastructure.
