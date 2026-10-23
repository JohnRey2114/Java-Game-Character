Fantasy Battle - Game Character Manager
📖 Project Description

Fantasy Battle is a simple Java application that uses a Graphical User Interface (GUI) built with Java Swing. Players can select a character and enter keywords to perform attacks and special abilities.

This project demonstrates Object-Oriented Programming (OOP), Abstraction, Abstract Data Types (ADT), GUI development, and user input validation.

1. Abstraction
Uses an abstract GameCharacter class as the parent class for all characters.
Defines abstract methods such as attack(), specialMove(), and getType().
Each character class implements its own attacks and abilities.
2. Multiple Character Types

The program supports different character classes, each with unique behaviors.

Character	Normal Attack	Special Move
Warrior	Swings a mighty sword	Shield Bash
Mage	Casts a fireball	Lightning Storm
Archer	Shoots an arrow	Rain of Arrows
Assassin	Performs a quick strike	Shadow Strike

3. Abstract Data Type (ADT)
Uses a CharacterRoster class to manage the available game characters.
Stores characters using Java's ArrayList.
Provides methods to retrieve characters and check the roster size.
Separates character management from the GUI.
4. Graphical User Interface (GUI)
Built using Java Swing.
Includes a character selection dropdown.
Provides a command input field.
Displays attack results and error messages in an output area.
Uses a dark theme with colored interface elements.
5. Keyword-Based Commands

Players can control their selected character by entering commands.

Command	Description
attack	Performs the character's normal attack.
special	Performs the character's special move.
exit	Closes the game window.

Commands are case-insensitive. For example, ATTACK, Attack, and attack are treated the same way.

6. User Input Validation
Detects empty commands.
Displays an error message for unknown commands.
Checks that a character is selected before performing an action.
Clears the command field after a valid attack command.
🛠️ Technologies Used
Programming Language: Java
GUI Framework: Java Swing
Data Structure: ArrayList
Concepts: Abstraction, Inheritance, Polymorphism, and Abstract Data Types (ADT)
📋 Requirements

Before running the program, make sure you have:

Java Development Kit (JDK) 8 or newer
A Java IDE, such as IntelliJ IDEA, Eclipse, NetBeans, or Visual Studio Code with Java support

Java Swing is included in the standard JDK, so no additional libraries are required.

🚀 How to Run the Program
Option 1: Using a Java IDE
Open your Java IDE.
Create or open your Java project.
Create a file named Main.java.
Paste the complete Java source code into the file.
Make sure the Main class contains the main() method.
Run the Main class.
The Fantasy Battle GUI should appear.
Option 2: Using the Command Line
Save the source code as Main.java.
Open a terminal or command prompt in the directory containing the file.
Compile the program:
javac Main.java

Run the program:
java Main

🎮 How to Use the Program
Launch the Fantasy Battle application.
Select a character from the dropdown menu.
Enter a command in the input field.
Click Execute Command or press Enter.
Read the result in the output area.
Example

If you select Brader (Warrior) and enter:

attack


Output:

Brader swings a mighty sword!


If you enter:

special


Output:

Brader uses Shield Bash!


If you enter an invalid command, the program displays an error message explaining which commands are available.

📁 Project Structure

The project can be implemented in a single Java file.

FantasyBattle/
├── Main.java
└── README.md


The Main.java file contains the following classes:

Main — Starts the application.
GameCharacter — Abstract parent class.
Warrior — Implements warrior attacks and abilities.
Mage — Implements mage attacks and abilities.
Archer — Implements archer attacks and abilities.
Assassin — Implements assassin attacks and abilities, if included.
CharacterRoster — Manages the collection of characters.
GameGUI — Creates the graphical interface and handles user commands.
🎯 Learning Objectives

This project demonstrates how to:

Apply abstraction to define common character behaviors.
Use inheritance to create specialized character classes.
Use polymorphism to execute different attacks through a common parent type.
Implement a collection-management ADT using ArrayList.
Build a graphical interface with Java Swing.
Process and validate user commands.
Separate game logic from the user interface.
🔮 Possible Future Improvements
Add health points and damage calculations.
Introduce enemy characters and battle rounds.
Add character images and attack animations.
Implement a scoring system.
Add sound effects and background music.
Save game progress to a file.
👨‍💻 Conclusion

Fantasy Battle is a beginner-friendly Java project that combines OOP concepts with a graphical interface and keyword-based character actions. It provides a foundation for developing more advanced character-based games.

Project Goal: Demonstrate abstraction, ADT, GUI development, and user input handling in Java.
