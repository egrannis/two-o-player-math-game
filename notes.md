Write down the nouns that you feel could make for important entities
(manifested in the form of classes) to contain (encapsulate) logic as part of this app.

- Game class
- Player class

------------
Write out a brief paragraph describing the role that class will play in your app.

- We will use the classes to allow players to interact with the game. Class methods will enable us
to impact the lives of players and the game score. We'll use this to initialize a new game in main.rb, and then within game.rb, initialize players.

------------
Write down the methods for each class while also speaking to the following points:

What information is relevant to each class?

- Game: how many players/who players are, questions, answers, rounds, who the winner is
- Player: how many lives they have, their identifier that gets used in the game

-------------
What will they need in order to be initialized?

- Game: players and values, how players will be selected, winner, round, game over

- Player: initialize with identifier, all 3 lives
-------------
What public methods will be defined on them?
- shuffle
-------------
Which class will contain the game loop
(where each instance of the loop is the other players turn)?
- Main file --> 
- check to see if the game is over or not as condition 
- check to see if player isn't out of lives
- switch between players for turns and subtract life if loser

-------------