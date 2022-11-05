# 📽️Cinema-app📽️
![img.png](img.png)
This app contains only with backend part that mimics the ticket booking system of a movie theatre.

As an administrator, you have access to almost all options:
_____________________________________________________________________________________________________
🔸add new movies;

🔸add new cinema halls;

🔸add (update, delete) new sessions;

🔸receive user by email;

As a user, you can:
_______________________________________________________________________________________________________
🔸register (when registering, a basket associated with the user will be automatically created);

🔸add a session to your shopping cart (only the user has access);

🔸get of all films, cinema halls, and sessions;

🔸get t of all your orders (only the user has access);

🔸change the session from the shopping cart (only the user has access).

Implementation details:
_______________________________________________________________________________________________________
Project-based on 3-layer architecture:
🔸Application layer (services);

🔸Data Access Layer (DAO);

🔸Presentation layer (controllers);

⚙️Technologies used:
_______________________________________________________________________________________________________
🔸Hibernate
🔸Spring Core
🔸Spring MVC
🔸Spring Security
🔸MySQL
🔸Apache TomCat
🔸Maven

Instructions for starting this project:
___________________________________________________________________________________________________________
1. Clone this project into the IDE as a Maven project.
2. Run the mvn clean package and if you find any errors, fix them.
3. Create a new schema in the database.
4. To set up a database connection, open db.properties (src/main/resources/db.properties) and make changes:
   db.url=YOUR_DATABASE_URL //your URL to the database;
   db.user=YOUR_DATABASE_USERNAME //username to get permission to read and write to the database;
   db.password=YOUR_DATABASE_PASSWORD //password for YOUR_DATABASE_USERNAME;
5. Connect Tomcat (version 9.0.50).
6. Run the project.
