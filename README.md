# story-service

The Story Service is a microservice in the Instagram clone application that handles user stories. It allows users to create, retrieve, and delete stories.

## Features

- Retrieve all stories
- Retrieve a specific story by ID
- Retrieve stories for a specific user
- Add a new story
- Delete a story

## Technologies Used

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL (or your preferred database)
- Maven (or your preferred build tool)

## Getting Started

These instructions will get you a copy of the Story Service up and running on your local machine for development and testing purposes.

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- MySQL (or any other supported database) installed and running
- Maven (or your preferred build tool) installed

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>

## Features
- Retrieve all follows
- Retrieve follows for a specific user
- Retrieve followers for a specific user
- Add a follow relationship between users
- Accept follow requests
- Unfollow a user
- Retrieve follow requests for a user
## Technologies Used
- Java 17
- Spring Boot 3.1.0
- Maven 4.0.0
- PostgreSQL 15.3
## Dependencies

- [Spring Boot] 
- [Spring Web]
- [Spring Data JPA]
- [postgresql]
- [Spring Cloud]
- [Spring Cloud OpenFeign]

## Getting Started
These instructions will get you a copy of the Follow Service up and running on your local machine for development and testing purposes.

### Prerequisites

- [Java SE Development Kit 17.0.5] (https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Maven 4.0.0] (https://maven.apache.org/install.html)
- [Spring Boot CLI] (https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#getting-started-installing-the-cli) (Optional)

### Installation
1. Clone the repository:
```bash
git clone <repository-url>
```
2. Navigate to the project directory::
```bash
cd follow-service
```
3. Open the application.properties file and configure the database connection details:
```
spring.datasource.url=jdbc:mysql://localhost:8086/story_db
spring.datasource.username=<database-username>
spring.datasource.password=<database-password>
```
4. Build the project using Maven:
```bash
cd follow-service
```
5. Run the application:
```bash
mvn spring-boot:run
```
## API Documentation
The Story Service provides the following API endpoints:

- GET /story/stories: Retrieves all stories.
- GET /story/{id}: Retrieves a specific story by ID.
- GET /story/stories/{userid}: Retrieves stories for a specific user.
- POST /story/addStory: Adds a new story.
- DELETE /story/{id}: Deletes a story.

