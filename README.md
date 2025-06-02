# Quiz Platform

## Overview
The Quiz Platform is a Java-based application designed to facilitate the creation, management, and participation in quizzes. It supports user registration, login, quiz creation, quiz participation, and score tracking. The project is built using core Java concepts and follows a layered architecture to ensure modularity and maintainability.

## Features
- **User Management:**
  - User registration and login.
  - Role-based access for admins and players.
- **Quiz Management:**
  - Admins can create and manage quizzes.
  - Players can participate in quizzes.
- **Score Tracking:**
  - Tracks and displays player scores.
- **Modular Design:**
  - Layered architecture with DAO, Model, Server, and UI layers.

## Technologies Used
- **Programming Language:** Java
- **Database:** MySQL (or similar relational database)
- **Architecture:** Layered architecture

## Project Structure
The project is organized into the following main packages:

1. **dao (Data Access Object):** Handles database operations.
2. **DB (Database):** Manages database connections.
3. **model (Models):** Represents application entities like User, Quiz, and Question.
4. **Server:** Contains server-side logic and main application classes.
5. **ui (User Interface):** Implements the graphical user interface.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/piyushphaske/Quiz-platform-using-JAVA.git
   ```
2. Open the project in your preferred Java IDE (e.g., Eclipse, IntelliJ IDEA).
3. Configure the database connection in the `DBConnection` class.
4. Run the `Main.java` file to start the application.

## Key Statistics
- **Lines of Code:** ~2000
- **Number of Classes:** 37
- **Database Tables:** 4 (Users, Quizzes, Questions, Scores)

## Future Enhancements
- Add unit tests for better reliability.
- Implement logging for easier debugging.
- Enhance the UI for a better user experience.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
