🌾Agricultural Crop Management System

Agricultural Crop Management System is a role-based Spring Boot web application that connects farmers directly with buyers, ensuring fair trade and transparent transactions in agriculture. 🌱 🚀 Built with Spring Boot, Hibernate, Thymeleaf, and MySQL for a smooth, scalable, and secure experience.

✨ Why Agricultural Crop Management System?

✅ Eliminates middlemen, ensuring better profits for farmers
✅ Buyers get fresh produce at fair prices
✅ Promotes digital transformation in agriculture

📌 Features
👨‍🌾 Farmer Module: Register, manage profile, list crops & set prices

🛒 Buyer Module: Browse, request, and purchase products

📊 Admin Dashboard: Monitor users, products & transactions

🔍 Search & Filter: Find crops by category, price, or location

🔐 Role-based Authentication: Farmer | Buyer | Admin

💬 Direct Communication: Seamless farmer–buyer interaction

| Layer          | Technology Used                                     |
| -------------- | --------------------------------------------------- |
| **Backend**    | Spring Boot, Spring MVC, Spring Data JPA, Hibernate |
| **Frontend**   | Thymeleaf, Bootstrap, HTML5, CSS3                   |
| **Database**   | MySQL                                               |
| **Build Tool** | Maven                                               |
| **Server**     | Apache Tomcat (embedded)                            |
| **Language**   | Java 8+                                             |

Configure MySQL Database

Create a database named agroshare_db

Update application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/agroshare_db

spring.datasource.username=your-username

spring.datasource.password=your-password

spring.jpa.hibernate.ddl-auto=update


