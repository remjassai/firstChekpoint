# firstChekpoint
Some practice with newly acquired concepts.

Design a FootballPlayer class that has the following attributes:
Id
First name
Last name
Number of appearances
Number of goals scored
Number of assists

Implement a constructor with all arguments and a constructor that sets first name and last name.
Also write the getter for each attribute
and a setter only for attendance, goals and assists.

Finally, the class will have the following methods:
score() : this method calculates how incisive a player is on the field.
The score is given by (numberGols + (0.75*numberAssists)) / numberPresences.
Design the Team class that has the following attributes:
Id
Name
The set of players in the team.
Set up a constructor so that it initializes id and name, initializing the set of players empty,
and
another constructor that also takes a set of players as a parameter instead.
Also add in the FootballPlayer class the team in which it plays as an attribute,
with corresponding getters and setters.
Finally, implement the following method:
printTeam() : print line by line first and last name of each player.
addPlayer(FootballPlayer p) : adds player p to the team.
Create a Main class in which to:
a) Instantiate 5 variables of type FootballPlayer (with parameters of your choice) and insert 3 of them into a set.
b) Instantiate an object of type Team teamA by passing the newly created set as a parameter to the constructor.
c) Instantiate an object of type Team teamB using the constructor without the input set and then add the other 2 players to it with the addPlayer method.
d) Print all the players of teamA who have:
at least scored 5 goals or made at least 7 assists and
has at least 20 appearances.
e) Instantiate a teamC whose players are those of teamA plus those of teamB.
f) Create a map where the keys are the players of teamC and the values are their scores computed by the score() method.
g) Print all the players in the map who have a score greater than 0.6
