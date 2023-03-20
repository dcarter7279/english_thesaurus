# english_thesaurus

This code is a simple implementation of a command-line dictionary using Python.

Prerequisites
The code requires the following:

Python 3.6 or above
JSON library
Getting Started
Clone or download the project to your local system.
Open your terminal and navigate to the project directory.
Run the thesaurus.py file.

Usage
The program prompts the user to input a word.
If the word exists in the JSON file, the program returns its definition.
If the word does not exist, the program suggests a word that is most similar to the entered word.
The user is then prompted to confirm whether the suggested word is the one they meant or not.
Functionality
The translate() function performs the following operations:

It converts the user's input to lowercase, so it can match the keys in the JSON file.
It checks whether the input word exists in the JSON file. If it does, the function returns its definition.
If the word does not exist in the JSON file, it uses the get_close_matches() method from the difflib library to find the closest matching words.
If a close match is found, the function asks the user to confirm whether they meant the suggested word.
If the user confirms, the function returns the definition of the suggested word.
If the user does not confirm or enters an invalid response, the function returns an error message.
If no close match is found, the function returns an error message.

Author
This project was created by Donell Carter.
