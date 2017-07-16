# ThirteensCardGame
A Solitaire Card Game.

------------------------------------------------------------------------

This modified game is inspired by the game "Tetris Solitaire" created by Randy Rasa. 

------------------------------------------------------------------------

## AUTHORS: 
* Chris Jim (However, I did not contribute to the making of the GUI class and I did not make the game rules) 
* Randy Rasa
* Elevens Lab(College Board) optional portion. 
 
### USER INSTRUCTIONS:
* Clone the repository, download ALL gifs in the cards folder. 
* Run the game on IDEs such as bluejay.

### How to play: 
* This game uses a 10-card board. 
* Ace, 2, 3, 4, 5, 6, 7, 8, 9, 10, J, Q correspond to the point values of 
  1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12.
* Pairs of cards whose point values add up to 13 are selected and removed.
* Kings are selected and removed singly. 
* Only two cards can be picked and removed at once. 
![samplePlaying](https://user-images.githubusercontent.com/26378494/28245907-7cec9b8c-6a43-11e7-9b90-babb87221a83.gif)
* If no remaining moves are available, you lose. 
![lose](https://user-images.githubusercontent.com/26378494/28245909-7f28beee-6a43-11e7-8596-313a64bc82d2.JPG)
* You will get the hang of it. 
![win](https://user-images.githubusercontent.com/26378494/28245913-80f66320-6a43-11e7-871d-882421d52e7c.gif)

### HOW TO START THIS PROJECT: ( Top-Down Development/ Object-Oriented Approach) 
* Create an abstract board class for inheritance
* Create a Card class and create mutator methods and comparison methods 
that can be specifically used on Card objects.
* Create a Deck class. We will use this to create a deck of cards, keep track of the
dealt cards and undealt cards, as well as shuffle and deal cards.
* Create a GUI class to provide GUI for the game Thirteens. 
* Lastly, create a driver class to run and start the game by first creating a a ThirteensBoard object. 
       
### [LICENSE](https://github.com/chrisjim316/ThirteensCardGame/blob/master/LICENSE)
------------------------------------------------------------------------
------------------------------------------------------------------------
