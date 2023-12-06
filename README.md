# Movie Theaters
## Group: TCH
#### Thuy Luu - 014247584
#### Chau Doan - 014131142
#### Nguyen Minh Huy Duong - 014701349

## Overview
The Movie Theater project is a web application that allows users to explore and discover information about movies. The project consists of a frontend built with React, a backend developed using Java Spring Boot, and utilizes Amazon S3 for storing images. PostgreSQL is used as the database to manage movie-related data.

## Technologies Stack

### Backend (Java):
* Framework Spring Boot
* Amazon S3 for storing image
* PostgreSQL as database

### Frontend (JavaScript):
* React, a JavaScipt library for building user interface
* Redux, a state management library for JavaScript applications, used in conjunction to efficiently manage
and update components in complex applications


__The entire application is containerized using Docker for easy development and management__

## Getting Started
### Prerequisites
Make sure you have the following installed:

- Node.js and npm for the frontend (version 14 or 16)
- Java JDK and Maven for the backend
- PostgreSQL for the database
- Amazon S3 bucket

### How to Setup and Run
1. Clone the repository to your local machine <br>
> `git clone --recursive https://github.com/chau-doan/cmpe-202.git`
2. Navigate to the project directory
> `cd cmpe-202`
3. Build the Docker containers.
> `docker-compose build`
4. Start the containers.
> `docker-conpose up`
5. Access the frontend at `http://localhost:3000`.
