# Car-Rental-Application
A car rental web application using React, Express.js, and MongoDB, enabling seamless management of car rentings, user interactions, and inventory.
The website design focuses on simplicity, mobile responsiveness, and clear navigation to offer an efficient, enjoyable rental experience.
# Prerequisites
Node.js 
React 
npm 
MongoDB 
Docker installed on your machine
Docker Compose installed on your machine
# Installation
Getting Started
**Clone the Repository**
  First, clone the repository from GitHub: git clone [repo url] cd Docker
**Next, use Docker Compose to build and run the containers:**
  docker-compose up --build

This command will build the Docker images and start the containers for the application and MongoDB database.Once the containers are running, you can access the application in your web browser at:

http://localhost:3000

To stop the containers, press Ctrl+C in the terminal where docker-compose is running, then use:

docker-compose down

This will stop and remove the containers.
# Project Structure
backend: Contains the Express.js server code and docker file.

frontend: Contains the HTML, Tailwind CSS, and JavaScript files for the user interface and docker file.

docker-compose.yml: Docker Compose configuration file for setting up the application and MongoDB containers.

# Overall Workflow
Authenticate:Sign up or log in.

Access Dashboard: Redirected to Admin or user dashboard.
Perform Actions:

Admins can add, update and delete cars,view all users list, messages from users and bookings.

users can see all cars, rent cars and sent messages to the admin.
# Contact
Email: krishnapushpan2003@gmail.com
