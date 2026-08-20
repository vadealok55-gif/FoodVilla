# FoodVilla

FoodVilla is a comprehensive, modern web application designed for managing customers, inventory, and orders in the food industry. It features a sleek dark-mode UI, secure role-based authentication, and seamless database integration.

## Features
- **User Dashboard**: Customers can browse food items, place orders, and view their order history.
- **Admin Portal**: Secure backend for managing products, users, and tracking all system orders.
- **Modern UI**: Completely redesigned with a professional dark slate aesthetic, responsive cards, and dynamic navigation.
- **Database Integration**: Built with robust Spring Data JPA and Microsoft SQL Server.

## Technology Stack
- **Backend**: Spring Boot, Java, Spring MVC, Spring Data JPA
- **Frontend**: Thymeleaf, HTML5, CSS3 (Custom Dark Theme), JavaScript
- **Database**: SQL Server
- **Build Tool**: Maven

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/vadealok55-gif/FoodVilla.git
   ```
2. Navigate to the project directory:
   ```bash
   cd FoodVilla
   ```
3. Update `src/main/resources/application.properties` with your database credentials.
4. Run the application:
   ```bash
   .\mvnw.cmd spring-boot:run
   ```
5. Access the application at `http://localhost:8081`
