# Rock Paper Scissors Game

## Objective:

Create a game of Rock Paper Scissors 

- - - -

### Tasks:

#### _User Choice_:

- Allow the user to input their preferred choice
- store that choice in a variable (to compare against the computer's choice)
	
	##### _Extra Credit_: 
	- Write a loop that only allows the the following selections for the user:
		- Rock
		- Paper
		- Scissors
	- Continue to prompt the user to select a valid option

	
#### _Computer Choice_:   

- Create an Array containing:
	- Rock
	- Paper
	- Scissors
- The computer should choose a random item from the array<br>*hint: use the `sample` method*
- Store the computers choice in a variable


##### Advice:
At this point, it's a good idea to run the program and use `puts` to log the user and computer selections. You're not actually playing the game yet, just insuring that the logic is in place for actual gameplay. 

#### _Gameplay_:

- Compare the user and computer selections and declare the winner
- You'll need to use branching/control-flow and prepare for several differnt outcomes
- See below for the various outcomes that are possible:

<center>![](images/rockpaper_web.jpg)</center>

- Print both choices and declare the winner
	
	##### _Extra Credit_: 
	- Give the user an option to play again
		- If yes, run the game again
		- If no, exit the program

##### Advice
While testing the potential outcome of the game, you may want to assign static variables to the computer's choices (and possibly the user's choices)

For example:
When working with Rock, Assign the computer's choice to the index of rock
	
	```ruby
	rps_array = ["Rock", "Paper", "Scissors"]
	computer choice = rps_array[0]
	```
	
Obviously, you'll only want to do this temporarily, but it helps with keeping some consistency while testing. 


- - - - 

### Summary: 

At this point, you'll have a functioning version of Rock Paper Scissors. Congrats! If you'd like to push further you can try the extra credit options

### Extra Extra Credit:

- Keep Score and play to best of 3
- Each time the user or computer wins give them a point <br> *hint: This means you'll need to have variables initializing each player's score at 0 outside of the loop*  
- After the game is over, ask the user if they would like to play again 