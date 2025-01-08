# Migrating Monolithic Web Applications to Microservice Architectures Considering Dependencies on Databases and Views
This is the contains replication packages accompanying our paper, Migrating Monolithic Web Applications to Microservice Architectures Considering Dependencies on Databases and Views. 

## Subject web applications
+ ### JPetStore2
    - JPetStore2 is a full web application that provides an online pet store system, built on the frameworks Spring 3 and MyBatis 2.
    - https://github.com/KimJongSung/jPetStore
+ ### JPetStore6
    - JPetStore6 is another version of JPetStore2, built on Spring 5, MyBatis 3, and Stripes.
    - https://github.com/mybatis/jpetstore-6
+ ### PetClinic
    - PetClinic is a veterinary clinic information system built on Spring Boot, using Spring Data JPA for database interaction and Thymeleaf for the user interface. 
    - https://github.com/spring-projects/spring-petclinic
+ ### ShoppingApp
    - ShoppingApp is a small online store system  based on the JSP Model 2 architecture.
    - https://github.com/manhduydl/Shopping-web-Jsp-Servlet
+ ### DayTrader
    - DayTrader is an online stock trading system based on the JsP Model 2 architecture, using Java EE, JSF, EJB, and JDBC.
    - https://github.com/WASdev/sample.daytrader7
## Project structure
+ ### Ground truths
    - This folder contains the microservice identification results provided by web app experts for the subject web applications.
    - In the ground truths, each of labels indicates a particural service.
    - JPetStore2: 
        + 0 (Order service), 1 (Account service), 2 (Cart service), 3 (Catalog service), C (Common component), N/U (Not used)
    - JPetStore6:
        + 0 (Order service), 1 (Account service), 2 (Cart service), 3 (Catalog service), C (Common component)
    - PetClinic:
        + 0 (Vet service), 1 (Visit service), 2 (Customer service), N/U (Not used)
    - ShoppingApp:
        + 0 (Order service), 1 (Account service), 2 (Cart service), 3 (Catalog service), C (Common component)
    - DayTrader:
        + 0 (Benchmarking service), 1 (Account service), 2 (Portfolio service), 3 (Quotes service), 4 (System configuration service), C (Common component), N/U (Not used)
+ ### Baselines
    - This folder contains microservice identification results generated by baseline techniques.
    - ### **MEM:** 
        + https://github.com/gmazlami/microserviceExtraction-backend
        + https://github.com/gmazlami/microserviceExtraction-frontend
    - ### **Bunch:** 
        + https://github.com/ArchitectingSoftware/Bunch
    - ### **Mono2micro:** 
        + https://github.com/rahlk/ASE21-Tutorial
+ ### Web app graphs
    - This folder contains the web app graphs generated by the proposed approach.
+ ### Results
    - This folder contains the experimental results used in the Evaluation section of the paper.