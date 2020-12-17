# Project 3: Connect 4 by Daniel E. and Lucas N.
The website is meant to display our project to the general public by explaining the core features and important findings of building Connect 4. We hope you enjoy!

## Who We Are
We are Babson students cross-registering at Olin College of Engineering with a passion for household board games and curiousity for artificial intelligence algorithms. Over the course of the semester, we have learned about Python, classes, and software design principles. To explore this intersection of studies, passion, and curiousity, we have decided to code a Connect 4 game. Connect 4 is a first-to-win, 2-player game, where each player takes turns dropping a colored disc to the bottom of one of the 7 columns' unoccupied cells. The first player to get 4 of the same colored discs in a row (vertically, horizontally, or diagonally) wins the game.       
![Connect4](https://cf.geekdo-images.com/I_ZPIWEvFlrMa8caT4UD-w__opengraph/img/kyLinLT_XujloY21Omjf5p7q1SA=/fit-in/1200x630/filters:strip_icc()/pic859430.jpg)

## Our Goal
The main goal of the project was to recreate this household game using our knowledge of Python and classes. The game is an interactive and entertaining piece of code that can be played with another person or artificial intelligence. As per Steve’s recommendation, we wanted to build a Ply AI which is common in many games like chess where the computer assumes a certain amount of moves the opponent will make in the future and plays accordingly. For example the player has 3 in a row. Ply AI would anticipate that they are most likely going to try and make that 4 in a row. Daniel and I chose to do this project because we wanted to learn about the development of AI which is not only highly relevant in everyday life but is also becoming of increased importance in the business world as companies try and use machine learning to maximize efficiency.

## Unique Features
Our project is designed in the Model, View, Controller framework where each interface is responsible for a core feature of  and switched throughout the running of the game. Since Model represents the state of the system at any point in time, we included. Since the View class represents what the user sees, we included. Since the controller represents the interactive elements of the user experience, we included. Moreover, we created instances of each class to make classes specific for Connect4 but also universal for variations of the board game. Host Game is a separate function.
Inheritance is used where a class wants to derive the nature of parent class and then modify or extend the functionality of it. Inheritance will extend the functionality with extra features allows overriding of methods, but in the case of Composition, we can only use that class we can not modify or extend the functionality of it. It will not provide extra features. Thus, when one needs to use the class as it without any modification, the composition is recommended and when one needs to change the behavior of the method in another class, then inheritance is recommended.

## Demo


## How To Install
Fork and clone this [repository](https://github.com/danieleisen0/Project-3)
As stated in the README file, all you need to do is run the connect_4_choice.py file!

