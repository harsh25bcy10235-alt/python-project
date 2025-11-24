

1. Introduction and Goals

The goal of this project is to create a functional, interactive implementation of the classic two-player game, Rock, Paper, Scissors. The game will be played between a human user and a computer opponent.

2. Scope of Work

The project will include the development of a core game engine and a simple user interface (either command-line or basic web-based, as specified in Section 4).

2.1. Core Functionality

    User Input: The system must accept a valid choice from the user (Rock, Paper, or Scissors).

    Computer Choice: The system must generate a random, non-deterministic choice for the computer opponent.

    Game Logic: The system must accurately determine the winner based on the standard game rules:

        Rock crushes Scissors (Rock wins)

        Paper covers Rock (Paper wins)

        Scissors cuts Paper (Scissors wins)

        Same choices result in a Draw.

    Outcome Reporting: The system must display the choices made by both the user and the computer, and clearly state the result (Win, Lose, or Draw).

2.2. Scoring and Rounds

    The game will track scores over multiple rounds until a predefined number of wins is achieved, or the user decides to quit.

    The default game length will be a "Best of 5" format (first to 3 wins).

3. Deliverables

The final delivery will include the following artifacts:
Deliverable	        Description
Game Source Code	Fully commented and functional source code for the game logic and interface.
User Instructions	A brief guide on how to run and interact with the game.
Testing Report    	A basic report confirming that all core game logic (all 9 possible outcomes: 3 Wins, 3 Losses, 3 Draws) functions correctly.

4. Technical Requirements

    Programming Language: To be determined (e.g., Python, JavaScript, etc.). For this basic SoW, we will assume a standard, widely used language.

    User Interface (UI): Command Line Interface (CLI) is the default requirement. The output must be clear and readable.

5. Success Criteria

The project will be deemed successful when:

    The game runs without errors.

    All three possible choices (Rock, Paper, Scissors) are correctly handled for both the user and the computer.

    The scoring mechanism accurately tracks and declares the winner of the "Best of 5" series
