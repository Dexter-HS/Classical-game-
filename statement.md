# **Project Statement**

## **1\. Problem Statement**

In an era of complex, high-graphic gaming, there is often a lack of simple, quick-to-play casual games that invoke nostalgia. Users looking for a brief recreational break or students learning programming logic need a straightforward digital implementation of classic playground games. The specific problem this project addresses is the need for a computerized, fair-play version of the traditional "Snake, Water, Gun" game that allows a single player to compete against an automated opponent without the need for physical game pieces or a second human player.

## **2\. Scope of the project**

The scope of this project is limited to a Command Line Interface (CLI) application developed in Python.

* **In Scope:**  
  * Implementation of the core game logic (Snake vs Water vs Gun).  
  * Single-player mode where the user competes against the computer.  
  * Randomized decision-making for the computer opponent.  
  * Input validation for user choices (s, w, g).  
  * Immediate win/loss/draw calculation and display.  
* **Out of Scope:**  
  * Graphical User Interface (GUI).  
  * Multiplayer mode (Human vs Human).  
  * Score tracking over multiple rounds (the current scope is single-round execution).  
  * Mobile or web deployment.

## **3\. Target users**

* **Casual Gamers:** Individuals seeking a quick, simple game to pass time or relieve stress.  
* **Students & Beginners:** Programming students looking for a reference implementation of conditional logic (if-else structures) and random module usage in Python.  
* **Nostalgia Seekers:** Users who want to relive the classic childhood game in a digital format.

## **4\. High-level features**

* **Randomized AI Opponent:** The system uses a random number generator to ensure the computer's moves are unpredictable and the game remains fair.  
* **User Interaction:** A simple text-based interface that accepts character inputs ('s', 'w', 'g') to represent game moves.  
* **Game Logic Engine:** A robust decision engine that compares user input against computer choice using standard game rules (Snake drinks Water, Water douses Gun, Gun kills Snake).  
* **Result Feedback:** Instant textual feedback displaying both players' moves and declaring the final winner or a draw.