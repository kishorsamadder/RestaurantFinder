RestaurantVenue
Restaurant Venvue decider application

Application Project
This application allows users to join a session to decide the restaurant for the outing. An additional feature is users can chat with each other in real time to decide the venue but submission will be admissible only from restaurant form not from the chat window. It has been built using the Spring Boot framework for the backend, SockJS for WebSocket communication, , h2 database for data storage and Angular for the frontend. The project utilizes Maven as the build tool for the backend.

Features
Session__creation: Users can create a session and invite others via created link or can join an ongoing session via shared link.
Real-time Chat: Once logged in, users are directed to the chat page where they can send messages in the chatroom.
Dispaying Chosen Restaurants: All users can see the restaurants added by other users in the same session.
Master_Access: Only master user(session creator) can end the session and random restuarant will be notified to all the users.
User Awareness: Users are notified when new users join the chatroom, allowing them to be aware of other participants.
Logout: Users can log out from the session, and can join back the session if the session is active.
Session Inactivity: No one can join the session if master user ended the session.
Tech Stack
The application incorporates the following technologies:

Spring Boot: A Java-based framework used for building the backend server and handling business logic.
SockJS: A WebSocket library that enables two-way, real-time communication between the server and clients.
Angular: A framework for building frontend.
Setup Instructions
To run the application locally, follow these steps:

Clone the repository:  https://github.com/vanam52923/RestaurantFinder.git
Navigate to the project directory: cd restaurant-backend
Set up the backend server:
Install the dependencies: mvn clean install
Start the Spring Boot server: mvn spring-boot:run
Set up the frontend:
Install the dependencies: cd restaurant-ui && npm install
Start the React server: ng serve
Open your application http://localhost:4200
Application flow
Detailed application flow can be found here :

URL

Feel free to enhance the application as per your requirement.
