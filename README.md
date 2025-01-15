**Pet Clinic Application**
The Pet Clinic Application is a web-based application that manages information about veterinary clinics, including details about pets, their owners, and visits.

**Prerequisites**
**Java 11 or higher:** Ensure that Java is installed on your system. You can download it from the official website.

**Maven:** This project uses Maven as its build tool. Download and install Maven from the official website.

**MySQL:** The application uses MySQL as its database. Install MySQL from the official website.

**Installation**
Clone the repository:


Copy code
git clone https://github.com/Thejas84/Pet_Clininc.git
Navigate to the project directory:

cd Pet_Clininc
Configure the database:

Create a database named petclinic in MySQL.

Update the src/main/resources/application.properties file with your MySQL credentials:

**properties**
spring.datasource.url=jdbc:mysql://localhost:3306/petclinic?useSSL=false&serverTimezone=UTC
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
spring.jpa.show-sql=true
Build the application:

mvn clean install
Run the application:

mvn spring-boot:run
Access the application:

Open your browser and navigate to http://localhost:8080/.

**Features**
Manage pet owners
Manage pets
Schedule visits
Veterinarian management
Comprehensive search functionality
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

**screenshots**
![Screenshot (327)](https://github.com/user-attachments/assets/d8790e0d-e655-4050-b68a-f744b7e99530)
![Screenshot (331)](https://github.com/user-attachments/assets/260db7f5-622e-48d6-b892-29e926c02dcf)

![Screenshot (332)](https://github.com/user-attachments/assets/824738eb-be07-4269-aa3e-bc7419402e3c)

![Screenshot (333)](https://github.com/user-attachments/assets/58801c02-0a63-4b60-8c9e-725db0c03aa6)
