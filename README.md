# Grocery Price Comparison System

Simple Java Servlet-based web application for comparing grocery prices across shops.

## Requirements
- Java 8+ (JDK)
- Apache Tomcat (or any Servlet container)
- MySQL (or compatible) — see `src/main/java/com/grocery/price/DBConnection.java` for DB config

## Quick start
1. Import the project into your IDE as a Dynamic Web Project or Maven/Gradle project.
2. Configure the database credentials in `DBConnection.java` or provide a datasource in your container.
3. Deploy the WAR to Tomcat (drop `target/*.war` into `tomcat/webapps` or run from IDE).
4. Visit `http://localhost:8080/<context-path>` and register/login.

Notes:
- Uploaded files go into the `uploads/` folder under the webapp.
- Several third-party JARs are included in `src/main/webapp/WEB-INF/lib` — consider moving large binaries to releases or using Maven Central.

## Repo
Pushed to: https://github.com/Rashmika28/Grocery-Price-Comparison-System-

## License
Add a license file if you want to open-source this repository.
