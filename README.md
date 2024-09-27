# CarTradeHub - README

## Overview

**CarTradeHub** is a web-based platform designed to facilitate the buying, selling, and trading of cars. It connects car sellers, buyers, and dealerships to provide a seamless experience for trading vehicles online. The platform offers features like car listings, advanced search filters, user profiles, secure payment options, and car history reports, all with a user-friendly interface.

## Features

- **Car Listings**: Browse through thousands of car listings, complete with images, descriptions, and pricing details.
- **Advanced Search Filters**: Search for vehicles by make, model, year, price, mileage, location, and more.
- **User Profiles**: Create and manage profiles as a buyer, seller, or dealership. Save favorite searches and track interactions.
- **Car History Reports**: Check vehicle history to ensure transparency and avoid surprises when purchasing.
- **Dealer Portal**: A specialized interface for dealerships to manage bulk listings, sales, and customer inquiries.

## Tech Stack

- **Frontend**: React.js, CSS3
- **Backend**: Spring Boot
- **Database**: MySQL
- **Version Control**: Git, GitHub

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/CarTradeHub.git
    ```

2. Navigate to the project directory:
    ```bash
    cd CarTradeHub
    ```

3. Install frontend dependencies:
    ```bash
    npm install
    ```

4. Set up the backend:
    - Ensure you have Java and Maven installed.
    - Navigate to the backend directory:
      ```bash
      cd backend
      ```
    - Build the project:
      ```bash
      mvn clean install
      ```

5. Set up the database:
    - Create a MySQL database and configure the `application.properties` file located in the `src/main/resources` directory with your database credentials:
      ```
      spring.datasource.url=jdbc:mysql://localhost:3306/<your_database_name>
      spring.datasource.username=<your_username>
      spring.datasource.password=<your_password>
      ```

6. Start the backend:
    ```bash
    mvn spring-boot:run
    ```

7. Run the frontend:
    ```bash
    npm start
    ```

8. Open your browser and navigate to `http://localhost:3000`.

