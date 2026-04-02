
# Online Food Ordering Application

**Tech Stack:** Java · Spring Boot · REST API · Hibernate/JPA · MySQL · Postman · MVC Architecture

## About
Full-stack web application supporting user authentication, restaurant management, and end-to-end order processing built with Spring Boot RESTful APIs.

## Features
- User registration and authentication
- Restaurant and menu management
- Order placement and processing
- 10+ RESTful API endpoints
- Global exception handling
- Layered MVC architecture

## Tech Stack
| Layer | Technology |
|-------|-----------|
| Backend | Java, Spring Boot, Spring MVC |
| ORM | Hibernate / JPA |
| Database | MySQL |
| API Testing | Postman |
| Architecture | REST, MVC, Layered |

## Project Structure
```
src/
├── controller/     # REST controllers
├── service/        # Business logic
├── repository/     # JPA repositories
├── model/          # Entity classes
└── exception/      # Global exception handler
```

## How to Run
1. Clone the repo:  `git clone https://github.com/aishap21/Food-Order-App.git`
2. Open in IntelliJ IDEA
3. Configure MySQL in `application.properties`
4. Run `FoodOrderApplication.java`
5. Test APIs at `http://localhost:8080` using Postman

## API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | /api/auth/register | Register user |
| POST | /api/auth/login | Login |
| GET | /api/restaurants | Get all restaurants |
| POST | /api/orders | Place an order |

---
*Developed by [Aishwarya Patil](https://github.com/aishap21)*
