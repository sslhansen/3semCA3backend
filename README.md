[![Build Status](https://travis-ci.org/dat3startcode/rest-jpa-devops-startcode.svg?branch=master)](https://travis-ci.org/dat3startcode/rest-jpa-devops-startcode)

*This project is meant as start code for semester/exam projects for 3.sem"*

*Projects which are expected to use this start-code are projects that require all, or most of the following technologies:*
 - *JPA and REST*
- *Testing, including database test*
- *Testing, including tests of REST-API's*
- *CI and CONTINUOUS DELIVERY*

### Preconditions
*In order to use this code, you should have a docker running, and internet access for extern endpoints*
*You also need to create a local database called 3semSecurity1 and one called startcode_test*

# How to use
- Persist users and admin to database, to get entity tables.
- Run project using tomcat 9.
- Using Postman, test if you can login with url/login with a user or admin object in header.
- Test if you can acces endpoints /api/info/user, /api/info/admin and api/info/extern
