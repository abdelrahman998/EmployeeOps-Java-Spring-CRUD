### Employee CRUD Ops

Developed a robust Java-based CRUD application utilizing Spring Boot MVC and Security to streamline employee management processes. The application leverages Spring MVC for efficient data handling and integrates.

#### Key Achievements:

- **HTML Views Integration:**
  - Implemented HTML views to enhance the user interface and facilitate a user-friendly experience for efficient CRUD operations on employee data.

- **Logging Support with Spring AOP:**
  - Enhanced application monitoring and debugging capabilities by integrating logging support using Spring AOP.
  - Employed `@Before` advice to capture method entry points, providing valuable insights into the application's execution flow.
  - Utilized `@AfterReturning` advice to log method return values, aiding in post-execution analysis and troubleshooting.

#### Technologies Used:

- **Java:** Leveraged the power of Java for building a robust and scalable backend.
- **Spring Boot:** Utilized Spring Boot to expedite the development process and create a standalone, production-ready application.
- **Spring MVC:** Employed Spring MVC for building a flexible and modular web application architecture.
- **JPA:** Integrated Java Persistence API for seamless interaction with the MySQL database.
- **MySQL:** Utilized MySQL as the relational database for storing and managing employee information.
- **HTML:** Integrated HTML views to create an intuitive and interactive user interface.

This project showcases my proficiency in Java, Spring Boot, and related technologies, as well as my commitment to enhancing application performance through advanced features like logging using Spring AOP.


## Installation

### Prerequisites

- Java Development Kit (JDK)
- MySQL Database
- MySQL Workbench

### Setup

1. Clone the repository: `git clone https://github.com/your-username/employee-management.git`
2. Create a new database in MySQL Workbench:
   - Open MySQL Workbench and connect to your MySQL Server.
   - Run the SQL script provided in this directory `EmployeeOps-Java-Spring-CRUD/sql-scripts/employee-directory.sql` to create the necessary database and tables.

3. Update application.properties:
   - Open `src/main/resources/application.properties`.
   - Modify the database connection properties based on your MySQL setup.
      `spring.datasource.url=jdbc:mysql://localhost:3306/employee_directory`
      `spring.datasource.username={your username}`
      `spring.datasource.password={your password}`

4. Run the application.

The application will be accessible at [http://localhost:8080](http://localhost:8080).

## Usage

- Access the application through your web browser or API client.
- Perform CRUD operations on employee data.
- Explore the user-friendly interface powered by HTML views.
- Monitor and debug effectively with the integrated logging support.
