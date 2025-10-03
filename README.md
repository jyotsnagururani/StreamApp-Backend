StreamApp Backend

StreamApp Backend is a Spring Boot + MySQL application that powers the StreamApp platform.
It provides RESTful APIs for managing users, content, and streaming-related data.


---

🚀 Features

✅ REST API for handling streaming data

✅ User management (CRUD operations)

✅ MySQL integration with Spring Data JPA

✅ Secure backend structure

✅ Scalable and extendable architecture



---

🏗️ Tech Stack

Backend

Java 17+

Spring Boot

Spring Data JPA

Hibernate

MySQL


Other Tools

Maven (build tool)

Postman (API testing)



---

⚙️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/jyotsnagururani/StreamApp-Backend.git
cd StreamApp-Backend

2️⃣ Setup MySQL Database

Create a new database:


CREATE DATABASE streamapp;

Update your application.properties with your DB credentials:


spring.datasource.url=jdbc:mysql://localhost:3306/streamapp
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

3️⃣ Run the Backend Server

mvn spring-boot:run

Server will start at: http://localhost:8080


---

📡 API Endpoints

Method	Endpoint	Description

GET	/api/users	Get all users
GET	/api/users/{id}	Get user by ID
POST	/api/users	Create new user
PUT	/api/users/{id}	Update user
DELETE	/api/users/{id}	Delete user
GET	/api/streams	Get available streams
POST	/api/streams	Add a new stream


(Add more endpoints here as your project grows)


---

📂 Project Structure

StreamApp-Backend/
│── src/main/java/com/example/streamapp/
│   ├── controller/     # REST Controllers
│   ├── model/          # Entity Classes
│   ├── repository/     # JPA Repositories
│   ├── service/        # Business Logic
│   └── StreamApp.java  # Main Spring Boot Class
│
│── src/main/resources/
│   ├── application.properties  # DB Config
│
└── README.md


---

🤝 Contributing

Contributions are welcome!

1. Fork the repo


2. Create a new branch (feature-xyz)


3. Commit your changes


4. Push to the branch


5. Create a Pull Request




---

📜 License

This project is open-source and available under the MIT License.


---

👩‍💻 Author

Developed by Jyotsna Gururani 🚀
