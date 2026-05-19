# Basic-Decrypter

A word-guessing and text decryption game built using Python and Tkinter. This project focuses on Sec level logic, functions, iterative loops, conditional statements, labels, and buttons.

## Cross-Device Compatibility Issues
To ensure the game runs across different devices without encountering errors, the repository includes two versions:
1. Basic decryptor(bg).py: The full visual version featuring a custom graphic background.
2. Basic decryptor.py: A stable version which doesnt include a background. This prevents program crashes on alternative devices.

## Project Structure
* Basic decryptor(bg) - game script with background image.
* Basic decryptor.py- game script for compatibility.
* README.md - Documentation of the project.
* What_I_Learned.txt - What i learned from the development and debugging process.
* Basic Decrypter video (No BG).mov - Video of the functional gameplay loop with Background.
* Basic Decryptor video(No BG).mov - Video of the functional gameplay loop without background

## How to Run the Game
1. Ensure you have Python installed on your machine.
2. Download either decryptor_with_bg.py or decryptor_no_bg.py from this repository.
3. Open your terminal or command prompt, navigate to the directory where the file is saved, and execute the run command: python decryptor_no_bg.py

## Gameplay Mechanics
* Scrambled letters: The game initializes a hidden word represented by blank spaces.
* Letter Decryption Input: The player interacts with buttons representing letter inputs. 
* Management: Once a button is clicked, it dynamically shifts to a disabled state to manage user input state validation and prevent useless guesses.
* Win/Loss Condition Loops: Clicking all the buttons unlocks a win or lose screen, and presents a functional Play Again option to restart the sequence loop.
