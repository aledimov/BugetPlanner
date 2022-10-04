# Getting Started

To check if application is running you need to make a request to Spring Boot actuator 
health endpoint with following path:
 ### {application_host}/actuator/health
In case application is running request should return following response:

    {"
        status":"UP"
    }

To check if H2 database is running you need make following request:
### {application_host}/h2-console
To login change JDBC URL and use credentials from application properties
