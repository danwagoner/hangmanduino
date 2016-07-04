# hangmanduino

##Author
Dan Wagoner
08/22/2009
nerdybynature.com

###Description
This sketch allows you to play hangman on your Arduino. There is a small list of words defined in a variable, which the program randomly selects from. A potentiometer is used for scrolling through the alphabet and a tactile switch for making selections. When you select the letter, the program displays a * instead of the letter and you aren't allowed to make that selection again. If you guess the word, you win and the board is reset. If you guess too many wrong, game over and the board is reset. If you hold the select button for 2 seconds, the board is reset.

###Pins
* Selector potentiometer: 0
* Selector button: 6
* Speaker: 5

###References
* Debounce code from David A. Mellis'
* Limor Fried example in the Arduino examples
* String library written by Hernando Barragan - http://www.arduino.cc/en/Tutorial/TextString
