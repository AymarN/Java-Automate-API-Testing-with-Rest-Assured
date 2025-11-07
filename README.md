<h5># How I test APIs with Rest Assured</h5>
<h5>From my submission on the LinkedIn Course.</h5>
<h5>[Handout]</h5>
<h5>|Java: Automated API Testing with Rest-Assured|</h5>

    |Chapter                              |Video                        |Resource                                      | Link                                                  |
                                                                        
    |0 - Introduction                     |3 - API Setup                |MAMP                                          | https://www.mamp.info/                                |

    |1 - Getting Started with Rest-       |1 - The Challenge with       |Book Response                                 |https://www.googleapis.com/books                       | 
                                          |API Testing                  
                                                                                                                                
                                       
                                          |2 - Rest-Assured Testing     |Rest Assured                                  |https://rest-assured.io                                |
                                          |Library                      |------------------------------------------------------------------------------------------------------|
                                                                        | IntelliJ                                     |https://www.jetbrains.com/idea/down                    | 
                                                                                                                       |load/#section=mac                                      |
                                                                        |------------------------------------------------------------------------------------------------------|
                                                                        | Maven Repository                             |  https://mvnrepository.com          <h5>              |
                                     
    |3-Validating API                     |4-Verifying Fields of        |Hamcrest Matchers                             |https://hamcrest.org/JavaHamcrest/javadoc              |
                                                                                                                       |/1.3/org/hamcrest/Matchers.html                        |
    |Responses                            |Response                     |------------------------------------------------------------------------------------------------------|
                                                                        |Hamcrest NotNullValue()                       |https://hamcrest.org/JavaHamcrest/javadoc/1.3/org/
                                                                                                                       |hamcrest/Matchers.html#notNullValue()                  | 
                                                                                                                                                                               |
                                                                        |------------------------------------------------------------------------------------------------------|
                                                                        | Hamcrest greaterThan()                       |https://hamcrest.org/JavaHamcrest/javadoc/1.3/org/     |
                                                                                                                       |hamcrest/Matchers.html#greaterThan(T)                  |  
                                                                                                                                                                               |          
                                                                        |------------------------------------------------------------------------------------------------------|
                                                                        | Hamcrest equalTo()                           |https://hamcrest.org/JavaHamcrest/javadoc/1.3/org/     |
                                                                        |                                              |hamcrest/Matchers.html#equalTo(T)                      |   
                                                                                                                                                                                       


### Prerequesites 
This assignment was performed with IntelliJ. I may use later on another IDE.
I used a professional version of MAMP server to set up the MySQL database.
Download MAMP for windows:
https://www.mamp.info/en/mamp/windows/


#### Cloning the repository
git clone https://github.com/AymarN/Java-Automate-API-Testing-with-Rest-Assured.git

#### Install dependencies(On Windows)

1. The Java JDK version 22 is required and systematically setup with IntelliJ.
2. Add IDE and all files in the htdocs folder to the Defender exclusions list.

#### Install dependencies(On Mac)

#### In Closing
<h5>Postman or Rest-Assured ?</h5>
I use postman for different types of Application Programming Interfacesuch as Rest, SOAP, GraphQL or WebSocket. 
It is a fast way to test API. I like to use Postman like a draft before using Rest-Assured. On Rest APIs, we 
hope to get the same outcome with the Rest-Assured library and the API client Postman.
My favorite for database tests is Rest-Assured.

