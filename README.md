# CONNECT FOUR
Introduction:
The Virtual Connect 4 game is a modern adaptation of the classic Connect 4 game, implemented using Java programming language, JavaFX for graphical user interface (GUI) design, and FXML for UI layout. This implementation enhances the traditional game by incorporating object-oriented programming (OOP) principles, an intuitive menu system, and a visually appealing game board for two players.

Technologies Used:
- Java: The core programming language used for implementing game logic and OOP principles.
- JavaFX: A platform for creating rich internet applications using a lightweight user interface API, used for GUI design.
- FXML: A declarative XML-based markup language used for defining user interfaces in JavaFX applications.
- JAR: Java Archive file format used to package and distribute Java applications and their associated resources.

Key Features:

1. Object-Oriented Programming (OOP) Principles:
   The game design is based on OOP principles, which facilitate modularity, code reusability, and maintenance. The implementation is organized into classes and follows concepts such as encapsulation, inheritance, and polymorphism.

2. Game Board:
   - The game board is represented as a grid of cells where players can place their tokens (discs).
   - OOP principles are applied to the board, with classes for the board itself and individual cells. This enables easy management and manipulation of the game state.
   
3. Menu System:
   - The game features an intuitive menu system that allows players to start a new game, access game settings, and exit the game.
   - Menu options are presented using JavaFX controls, providing a user-friendly experience.
   
4. Graphical User Interface (GUI):
   - JavaFX is used to create a visually appealing user interface with smooth animations and transitions.
   - The game board, menus, and buttons are styled using CSS for a polished look.
   
5. Game Logic:
   - The game logic is implemented using Java classes and methods that handle player moves, win conditions, and tie conditions.
   - The implementation efficiently checks for win conditions by examining horizontal, vertical, and diagonal sequences of tokens.
   
6. FXML Layout:
   - FXML files are used to define the layout and structure of the GUI components.
   - This separation of UI structure from logic enhances maintainability and allows designers to work on the UI independently.
   
7. Player Interaction:
   - Players take turns placing their tokens on the game board by clicking on the desired column.
   - Validity checks are performed to ensure legal moves and prevent invalid placements.
   
8. Win and Draw Detection:
   - The game actively checks for win conditions after each player move.
   - If a player achieves a winning sequence of tokens or the board is filled without a winner, the game notifies the players and offers the option to play again.
   
9. JAR Packaging:
   - The final game application is packaged as a JAR file for easy distribution and execution on Java-supported platforms.
   
Conclusion:
The virtual implementation of Connect 4 using Java, FXML, and JAR showcases a seamless integration of modern programming concepts and technologies. The combination of OOP principles, JavaFX for GUI, FXML for UI layout, and JAR packaging results in an engaging and visually appealing game that retains the essence of the classic Connect 4 while offering enhanced gameplay and user experience.
