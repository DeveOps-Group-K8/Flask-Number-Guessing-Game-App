# Flask-Number-Guessing-Game-App
Number Guessing Game App was initiated on DevOps MSc Software Engineering mini-project for  group of 5

1.1 Project Title
Number Guessing Game App using Python

1.2 Project Overview
The Number Guessing Game App is an interactive game developed using Python. The game challenges players to guess a randomly generated number within a specified range, providing hints such as "higher" or "lower" to guide their guesses. The project will incorporate various features, including a graphical user interface (GUI), timed mode, sound effects, play levels support, animations, a leaderboard, and a Database.

1.3 Objectives
•	Develop an interactive and user-friendly Number Guessing Game.
•	Implement different game modes.
•	Enhance the gaming experience with GUI, animations, and sound effects.
•	Integrate a leaderboard for tracking scores.
•	Implement play levels for player interaction.
•	Ensure scalability and maintainability following SDLC principles.

2. SDLC Methodology
The SDLC model best suited for developing this app depends on its complexity and requirements. Below are two possible models:
a) Waterfall Model (For Beginners & Small-Scale Development)
•	Requirement Gathering: Define game rules (e.g., range of numbers, hints).
•	Design: Create UML diagrams, flowcharts, and UI layout.
•	Implementation: Code the game logic, UI, and local storage.
•	Testing: Debug and check for errors.
•	Deployment: Publish on platforms (if needed).
•	Maintenance: Fix bugs and improve features.
b) Agile Model (For Continuous Enhancements)
•	Develop the game in iterative cycles (sprints).
•	Receive feedback and improve continuously.
•	Test after each iteration.
The Agile Model will be used for this project, enabling iterative development with continuous feedback and improvement.




3. Software Development Life Cycle Phases
3.1 Planning
•	Define project scope and requirements.
•	Identify target users.
•	Allocate resources, tools, and timeline.
•	Conduct risk analysis and mitigation planning.


3.2 Requirement Analysis
•	Functional Requirements: 
o	Single-player game modes.
o	Timed Mode with countdown functionality.
o	GUI-based gameplay with HTML, CSS, Bootstrap, and JavaScript.
o	Sound effects and animations.
o	Leaderboard tracking scores.
o	Real-time chat for multiplayer interactions.
•	Non-Functional Requirements: 
o	High performance and responsiveness.
o	Secure data handling and communication.
o	User-friendly UI/UX design.

3.3 Design
•	System Architecture: 
o	Client-server architecture for functionality.
o	Database integration for leaderboard.
•	UI/UX Design: 
o	Main menu with game mode selection.
o	Game screen with number input and hint display.
o	Leaderboard and play levels.
•	Technology Stack: 
o	Frontend: HTML for GUI
o	Backend: Python (Flask)
o	Database: PostgreSQL for storing scores and chat logs
o	Deployment: AWS CLI, EC2 and Elastic Beanstalk

Algorithm for the Number Guessing Game
1.	Generate a random number within a range (e.g., 1-100).
2.	Prompt the user to enter a guess.
3.	Compare the guessed number with the actual number.
o	If the guess is correct → Display a success message.
o	If the guess is too high → Display "Too High" and allow another attempt.
o	If the guess is too low → Display "Too Low" and allow another attempt.
4.	Track the number of attempts.
5.	Store best scores using local storage.
6.	Optionally, allow restarting the game.

UML Diagram (Class Diagram & Use Case Diagram)
a) Use Case Diagram
b) Use Case Diagram
Actors: Player Use Cases:
1.	Start Game → Generate Random Number
2.	Enter Guess → Compare with Secret Number
3.	Receive Hint → "Too High" / "Too Low"
4.	Win/Lose Game → Display Results
5.	Restart Game

 
Feature	Description
Random Number Generation	The game generates a secret number randomly.
User Input	Players enter their guesses.
Feedback System	Displays whether the guess is "Too High" or "Too Low".
Attempt Counter	Keeps track of the number of attempts.
Restart Option	Allows users to restart the game.
Score Saving	Stores best scores using local storage.
User Login/Logout	
Local Storage 	 For user scores
Time Tracking	
Responsive UI	


3.4 Implementation
•	Develop core game logic for number guessing.
•	Integrate GUI using HTML, CSS, JavaScript and Bootstrap.
•	Implement timed mode using Python’s time module.
•	Add sound effects using pygame.
•	Store leaderboard data using PostgresSQL

3.5 Testing
• Testing Strategy
•	Unit Testing Frameworks: unittest
•	Integration & API Testing: Flask-testing
•	Performance Testing: pytest
•	Security Testing: Flask-WTF, ORM, Flask-Babel, Secure headers, and Flask-Limiter

3.6 Deployment
•	Deploy the app to AWS Cloud.
•	Provide installation guides and user documentation.
•	Development Methodology (Agile, Scrum)

Use Case Diagram
![image](https://github.com/user-attachments/assets/e4d69cd8-d851-4e52-8b27-38352074d06c) 

![image](https://github.com/user-attachments/assets/51a53cb9-4cd2-424d-b6e2-216dbc6c95a2)

Class diagram
![image](https://github.com/user-attachments/assets/a414654c-9ecf-411e-811d-e6c9474970bb)

Interactive diagram
![image](https://github.com/user-attachments/assets/ba4a9faf-9c68-4b4a-bdd9-f5441360fa5f)

Flow Chart
![image](https://github.com/user-attachments/assets/7766f065-5e7a-470c-93d5-85d250bfea0a)

Sequence Diagram
![image](https://github.com/user-attachments/assets/999f0c76-cd21-4fa2-ad98-78ddba627737)




