# User_Authentication
Developed a User Authentication API with Role-based Access Control

  The Role-based access control (RBAC) refers to the idea of assigning permissions to used 
  based on their role within an organization. it offer a simple, manageabale approach to access
  management that is less prone to error than assigning permission to user individually.

Implement the following features in this project:

 User Registration: Allow users to register by providing their username, email, and
password.

 User Login: Authenticate users using their credentials and generate a JWT (JSON
Web Token) for subsequent requests.

 Role-based Access Control: Implement user roles such as &quot;admin&quot; and &quot;user&quot; with
different access permissions.

 Protected Routes: Create API routes that are accessible only to specific roles.
 
 User Profile: Allow users to retrieve and update their profile information.


Using following Tech tools to developed this project:

i) Spring boot

ii) Java as a main Programming language

iii) MySql database and MySql workbench so that i can intract with the database easily.

iv) Postman for testing APIs




In this project i added several dependencies:

i)  spring-boot-starter-data-jpa:- it is help me to create the entity.

ii) spring-boot-starter-web:- It is used for building the web application, including RESTful applications.

iii) mysql-connector-java:-It is used to build connection to our database.
	
iv)spring-security:- it is used for spring boot application automatically requires the basic authentication for all HTTP endpoint.

v) Json-webToken :- it is used for secuarely transmitting trusted information between parties in a contact way. the token claims that are encoded as a JSON object and
                     are degitally signed using private secret or a public key/private key pair.
                     
 ![Screenshot (2)](https://github.com/Faisal2205/User_Auth/assets/130309799/042997e4-ac89-4496-8c52-98f41512ff1f)


And to connect out backend to the mysql i (Specify Data Source Properties) in 
the (application.properties) file.
and also using Hibernate to automatically translates the entity into a table.


define the Configuration Package and inside that package i define all configure related code.
what CORD does:- The CORS (Cross-Origin Resource Sharing) allows a webpage to request additional resources into 
the browser from other domains such as API data. We need CORS because modern browsers usually 
have the same-origin security policy (browsers prohibit AJAX calls to resources outside the current origin).
in the Spring boot we can enable CORS support in Spring MVC applications at the method level and the global level.


![Screenshot Image 2023-05-29 at 12 40 52 AM](https://github.com/Faisal2205/User_Auth/assets/130309799/9710e9f1-2255-4a7b-acc3-988499803fd6)


 here, call the authentication api in postman


![Screenshot Image 2023-05-29 at 12 54 14 AM](https://github.com/Faisal2205/User_Auth/assets/130309799/b25aa702-e93f-4c06-bf68-586e11ca13b0)


here, call the forUser Api in postman



![Screenshot Image 2023-05-29 at 01 00 20](https://github.com/Faisal2205/User_Auth/assets/130309799/b14f3612-42eb-428a-aee9-6aede2ca0d2b)


here, call the forAdmin api in postman

![Screenshot Image 2023-05-29 at 01 01 24](https://github.com/Faisal2205/User_Auth/assets/130309799/61fe5abb-9f2b-45de-9abc-43e45cddb37d)


here, call the registerNewUser in postman

![Image 2023-05-29 at 01 09 57](https://github.com/Faisal2205/User_Auth/assets/130309799/29bc040c-c7de-479f-a8e7-8e8880d30dfa)


here, the data store in MySQL database


![Image 2023-05-29 at 01 15 41](https://github.com/Faisal2205/User_Auth/assets/130309799/6afce042-38ce-4800-9bf9-468efcd61d6b)


![Image 2023-05-29 at 01 19 25](https://github.com/Faisal2205/User_Auth/assets/130309799/4536622e-27d4-45f5-b1e2-6c94c905db0b)
