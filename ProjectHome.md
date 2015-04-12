The objective of this project is to create a video library management system as a web service capable of renting movies to its users. The web service would create accounts for simple users as well as premium users. Simple members would have a balance amount whereas Premium members would have a subscription fee. Initially an interface defining all the classes and functions we would be using was specified. DAO classes have been created for each of the entities used in the system. Test cases have been also created in order to test the functionalities of the web service. We have used JUnit to develop these test cases. The system also utilizes various validation techniques to validate the details of the users.

The project is a 3- tier stateless Video Library Management System.
The core focus of the project was to study the effect of various performance tuning techniques and the effect of using some or all techniques in parallel.
The system was designed and tested to serve a database of 50,000 movies of various categories and could serve 250,000 users with system distributed: DB on 8Gb ram and Presentation, Persistence, Business Logic on 8 Gb ram systems.

The system library owners, and the users of the video library can access the system over the web.

The services for the customers include search by various criteria (Popular, Drama, Action, Actor, etc), rent and rerun movies, shopping cart and book a movie.

The library managers could: add, update and remove movies and customers.

Transaction management and shopping cart was included in the system.

All the functionalities were developed as web services.

Performance Tuning Techniques:

Use of connection pooling
Rollback and auto commit of transactions
De-Normalization
Updating the database only when there is a change to the data.
Mem Cache
Use of Stored Procedure
Database Caching – ResultSet Oriented
Distributed Computing


Technologies used: Java EE, Apache Tomcat, MySQL, JUnit, HTML, jQuery, JavaScript, JMeter, JSP, Servlets.