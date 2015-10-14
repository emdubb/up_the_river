#WDI Project 1 | Up the River Game

##User Stories
- As a group of players, I want to be able to start a new game with the proper setup.
- As a group of players, I want to be able to input each player upon starting a new game so that I can see names and cards for each person because drinking nicknames are fantastic.
- As a group of players, when I start a new game - I want to write a rule or punishment or randomly choose one.
- As a player, on my first turn I want to guess if my card will be red or black.
- As a player, on my second turn I want to guess if my card will be higher or lower than my first card.
- As a player, on my third turn I want to guess if my card will be “in between”, “outside”, or “on the fence” of my first two cards.
- As a player, on my fourth turn I want to guess what suit my card will be.
- As a player, I want to know if I won or lost the round. If I won I want to assign drinks to other people. If I lost I want to take drinks.
- As a group of players, after all four rounds are complete I want to see the cards on the river. If my cards match any of the cards in the left column I want to take drinks, if my cards match any of the cards in the right column I want to assign drinks to other players.
- As a group of players, I want to see the top card and if I have a card with the same value I will follow the rule or punishment.
- As a group of players, I want to play on a computer, tablet, and phone so that I can play anywhere.
- As a player, I want to see what cards other players have drawn so that I can try to make a better guess.
- As a player, I want an elegant design exeperience so that I would rather use this app than a deck of cards.
- As a player I want to be able to add more players mid way through the game
- As a group of players, if there are more than 6 people I want to add a second deck of cards (there will never be more than 12)


##Wireframes

The current [wirefame][wireframelink] is desktop only


[wireframelink]: http://x9fj2l.axshare.com

##MVP + Planning
### Current Sprint (MVP)
- [x] As a group of players, I want to be able to start a new game with the proper setup.
- [x] As a group of players, when I start a new game - I want to write a rule or punishment.
- [x] As a player, on my first turn I want to guess if my card will be red or black.
- [ ] As a player, on my second turn I want to guess if my card will be higher or lower than my first card.
- [ ] As a player, on my third turn I want to guess if my card will be “in between”, “outside”, or “on the fence” of my first two cards.
- [ ] As a player, on my fourth turn I want to guess what suit my card will be.
- [ ] As a player, I want to know if I won or lost the round. 
- [x] As a player, if I lost then I want to receive a point. If I won then I do not want to recieve a point.
- [ ] As a group of players, after all four rounds are complete I want to see the cards on the river. If my cards match any of the cards in the left column I want to take drinks, if my cards match any of the cards in the right column I want to assign drinks to other players.
- [ ] As a group of players, I want to see the top card and if I have a card with the same value I will follow the rule or punishment.

### Icebox
- [x] As a group of players, I want to be able to input each player upon starting a new game so that I can see names and cards for each person because drinking nicknames are fantastic.
- [ ] As a player, if I won I want to assign points to other people.	
- [ ] As a player, I want to see what cards other players have drawn so that I can try to make a better guess.
- [ ] As a player, I want an elegant design exeperience so that I would rather use this app than a deck of cards.
- [ ] As a group of players, I want to play on a computer, tablet, and phone so that I can play anywhere.
- [ ] As a player I want to be able to add more players mid way through the game
- [ ] As a group of players, if there are more than 6 people I want to add a second deck of cards (there will never be more than 12)
- [ ] As a group of players, when I start a new game - I want to have the option to write a rule or punishment or randomly choose one.

##Pseudocode

- When clicking the "lets get schwastey button," get the value of all the text input for player names
-- Display these values on the Game Board. If there is no value then display nothing.
- Determine which player's turn it is
- On clicking the red button, randomly select a card. If the card has a class of red, then assign a 