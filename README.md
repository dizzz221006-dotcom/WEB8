# WEB8
**Event Registration API — README**

This project is an Event Registration API developed with Java and Spring Boot. It allows users to create, view, update, delete, and search events. Each event contains an ID, a title, and a location. The application uses Spring Data JPA to communicate with a PostgreSQL database.

To run the project, install JDK 17 and PostgreSQL. Create a database named event_db. Open the project in IntelliJ IDEA and wait for Gradle to download the required dependencies. In the application.properties file, configure the database URL, username, and password. Make sure that the PostgreSQL server is running before starting the application. Run the EventRegistrationApplication class.

The API runs on port 8080 by default. Use Postman to send HTTP requests to /api/events. GET returns events, POST creates an event, PUT updates an existing event, and DELETE removes an event. To create an event, send JSON data with title and location fields.

The project uses Spring Boot, Spring Data JPA, PostgreSQL, and Gradle. The database stores event information, so the data can remain available after the application restarts.
