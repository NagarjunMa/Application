# Application

## Introduction 
This is basic Books Management Application built using spring boot and MySQL. The application is deployed in Docker.
We can run and execute the application directly as the container. The API documentation is implemented using Swagger UI.

## Screenshots
  The screenshot depicts API Documentation using SwaggerUI 
  <img width="1501" alt="image" src="https://github.com/NagarjunMallesh/ApplicationBooks/assets/34504820/2e5f876f-5e59-4a8f-a98b-8c5ee80363a6">


## Execution 
- Install docker
- Execute following command -> docker run -p 9090:8080 --name application --net spring-net -e MYSQL_HOST=mysqldb -e MYSQL_PASSWORD=Kamana@7897 -e MYSQLPORT=3307 springapplication
- The Application will be running on PORT - 9090
- To access the API available --> http://localhost:9090/swagger-ui/index.html open the URL on Browser
- Once the application is up and running, Use postman to execute API Calls


## Author 
Name : Nagarjun Mallesh
