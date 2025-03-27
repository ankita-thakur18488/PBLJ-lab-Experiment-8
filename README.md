# PBLJ-lab-Experiment-8 (Servlets and JSP)

## Overview

This experiment covers fundamental and advanced concepts of Servlets and JSP (Java Server Pages), essential for building dynamic web applications. Servlets are Java programs that run on a web server, handling client requests and generating dynamic responses. JSP enables embedding Java code in HTML pages for easier server-side scripting.

![image](https://github.com/user-attachments/assets/e2cfb9b4-a49e-48ea-af6f-c791853ca269)

### Topics Covered

- Servlet Basics: Servlet Lifecycle, Generic Servlet, HttpServlet, Linking Servlet to HTML
- HTTP Servlet Request and Response: Handling GET and POST requests
- Database Integration: Connecting Servlets with JDBC for data retrieval and manipulation
- Servlet Configuration: Configuring servlets using web.xml, ServletConfig, and ServletContext
- JSP Essentials: JSP directives, Scriptlets, Expressions, and Declaration tags
- JSP Page Handling: Including files, using JSP actions, and handling user inputs dynamically

## Setting Up Servlets & JSP in VS Code
#### 1 Install Required Extensions
- Java Extension Pack
- Tomcat for Java
- Debugger for Java
  
#### 2 Install & Configure Apache Tomcat
- Download Tomcat from Apache Tomcat.
- Extract it (e.g., C:\Tomcat).
- Add it in VS Code → Tomcat for Java → Add a Tomcat Server.

#### 3 Project Structure
PBLJ-Servlets/
├── src/main/java/MyServlet.java
├── webapp/index.html
├── webapp/WEB-INF/web.xml
├── lib/ (JAR dependencies)
└── pom.xml (if using Maven)

#### 4 Configure Dependencies
- Without Maven: Download servlet-api.jar, place in lib/, and add to classpath.
- With Maven (Recommended): Add the configuration in pom.xml:


## 📌 Experiment 7:Develop web applications using Servlets and JSP for user input handling, database integration.

| Program    | Description                                 |
|------------|---------------------------------------------|
| **[8.1) Easy](/Exp8.1.java)** |Write a servlet to accept user credentials through an HTML form and display a personalized welcome message if the login is successful. |
| **[8.2) Medium](/Exp8.2.java)** |Create a servlet integrated with JDBC to display a list of employees from a database. Include a search form to fetch employee details by ID.|
| **[8.3) Hard](/Exp8.3.java)** | Develop a JSP-based student portal. Include a form for entering attendance details and save them to the database using a servlet.|

-----
