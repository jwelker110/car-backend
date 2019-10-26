# Car Backend

### Run the project
1) cd into `car-backend` and `mvn clean package` followed by
`java -jar target/car-backend-0.0.1-SNAPSHOT.jar`. This creates 
the eureka server that pricing-service will register with.
2) cd into `pricing-service` and `mvn clean package` followed by
`java -jar target/pricing-service-0.0.1-SNAPSHOT.jar`
3) cd into `boogle-maps` and `mvn clean package` followed by
`java -jar target/boogle-maps-0.0.1-SNAPSHOT.jar`
4) cd into `vehicles-api` and `mvn clean package` followed by
`java -jar target/vehicles-api-0.0.1-SNAPSHOT.jar`

### API Explorer

Navigate to [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html).
 

