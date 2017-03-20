Based on Ravesh RV's Brownfield Airline Demo (PACKT Spring Microservices)

Converted to use Gradle scripts and latest Spring Boot 1.5.3.


Follow below steps to run the application. 

1. Build all gradle projects

2. Start Rabbit MQ. 

3.Run below commands in separate terminal windows. 

java -jar Fares/build/libs/fares-1.0.jar
java -jar Search/build/libs/search-1.0.jar
java -jar Checkin/build/libs/checkin-1.0.jar
java -jar Book/build/libs/book-1.0.jar
java -jar Website/build/libs/website-1.0.jar

4. Open Browser Window and navigate to http://localhost:8001

5. When asked for credentials use guest/guest123

6. Click Search Menu for search and Booking

7. Click CheckIn Menu for check0in
