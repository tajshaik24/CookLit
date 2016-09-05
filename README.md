# CookLit

## Synopsis

Order homecooked meals around you with a tap. Uber for homecooked meals (iOS)

## Demo

[![IMAGE ALT TEXT](http://i.stack.imgur.com/RZrZo.png)](https://drive.google.com/drive/folders/0B6vHLSwjkF8dNUpFcWFfYTdOYk0 "CookLit Demo")

## Code Example

Relevant strategy and implementation functions in Hog.py:

```
def roll_dice(num_rolls, dice=six_sided): #Simulate rolling the dice passed in num_rolls times
    
def take_turn(num_rolls, opponent_score, dice=six_sided): #Simualate turn_taken by one of the players. To be called in play function.
    
def play(strategy0, strategy1, score0=0, score1=0, goal=GOAL_SCORE): #Repeated alternates calls to strategy functions passed in and take_turn until one player reaches GOAL_SCORE
    
```

## Installation

Clone repo and open in Xcode.

```
git clone https://github.com/furkhan324/CookLit.git
#open Cooklit.xcworkspace from XCode
```

## Contributors

Mohammed Abdulwahhab (@furkhan324), Taj Shaik(@tajshaik24)

## License

Code may not be copied, edited, or reproduced in any form without the consent of the contributors.
