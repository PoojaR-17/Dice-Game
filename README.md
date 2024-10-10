# Dice-Game
Dice-Game using the Random number Generator
This JavaScript project generates random numbers between a given range and displays them as part of a simple game. When the "Roll" button is clicked, three random numbers are generated, displayed, and compared. The project then highlights the highest and lowest numbers in green and red, respectively, while middle values are highlighted in yellow. If there is a tie between any two or three numbers, they are highlighted in blue.

![Dice-Game]()
Features
Generates three random integers between 1 and 6 when the button is clicked.
Compares the numbers and highlights:
Green for the highest number.
Red for the lowest number.
Yellow for the middle number (if applicable).
Blue for ties between any two or all three numbers.
Simple user interface using HTML and CSS.
How It Works
Random Number Generation:

The function getRandomInt(min, max) generates a random integer between min and max (both inclusive).
Event Listener:

A click event is added to a button with the ID #roll. When clicked, three random numbers are generated and displayed in elements with IDs #number1, #number2, and #number3.
Highlighting Logic:

The maximum and minimum values among the three generated numbers are determined.
Based on the comparison of the three numbers:
The highest number's container is highlighted in green.
The lowest number's container is highlighted in red.
The middle number (neither the highest nor the lowest) is highlighted in yellow.
If two or more numbers are equal, they are highlighted in blue.
Files
index.html: Contains the basic HTML structure including buttons and placeholders for displaying random numbers.
style.css: Contains styles for highlighting the elements based on their values.
script.js: Contains the JavaScript logic for generating random numbers and determining which number is the highest, lowest, or tied.
Usage
Clone or download the project.
Open the index.html file in a web browser.
Click the "Roll" button to generate random numbers and see the result.
Example
Three random numbers, such as 3, 5, and 2, are generated.
The number 5 will be highlighted in green (highest), 2 in red (lowest), and 3 in yellow (middle).
If the numbers are the same (e.g., 4, 4, 4), all three will be highlighted in blue.
