# Java-BookStoreShoppingCart

## Installation & Usage
### To run the application for the first time
1. Open the command line in your project root
2. ```mvn clean install tomcat7:run``` this sets up and runs the tomcat server in your workspace 

### Test the app
1. Open the terminal in the project root
2. ```mnv -P integration verify``` - runs the tests

### Eclipse configurations
+ Tomcat configuration should be have goal ```tomcat7:run```
+ IntegrationTest ```-P integration verify```

###### the application is configured to serve at [local port 8080](http://localhost:8080/books/list)