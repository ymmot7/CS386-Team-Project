#D.2 - Requirements
____________________________________

###1. Positioning
#####a. Problem Statement:
The problem of being bored and looking for an immersive gaming experience affects gamers; the impact of which is being unable to find a game or experience that helps pass time.
		
#####b. Product Position Statement:
For gamers who are looking for ways to alleviate boredom and pass time, TextAdventureGame is a text adventure game that immerses the user in a story in which they choose their own path unlike other text adventure games, our product keeps the user engaged by providing multiple choices that lead to multiple paths of gameplay.
		
#####c. Value Proposition
I. *Value Proposition*: TextAdventureGame is a text adventure game that allows gamers to pass time and reduce boredom. The game encourages creativity and personal choice to determine the path the story leads. Players will have the opportunity to play something more open-ended and thought provoking than most mainstream games currently available.
		
II. *Consumer Segment*: Gamers who are looking for an immersive text adventure.


###2. Stakeholders
#####a. Developers:
Create the idea behind and implement a text adventure game playable on android. Responsibilities include learning the necessary tools (Android studio, some sort of database - probably SQL), outlining the story for the game by creating paths and and story lines that work together.
	
#####b. Gamers/Users/WIP
People who will play the game and (hopefully) provide feedback to the developers. Responsibilities include playing through the game and following the storyline.
	
#####c. Testers
People who will also play the game and search thoroughly for bugs and discontinuity. Responsibilities include exhausting options in the game and finding bugs/issues to report to the developers. Provide assistance for creating a seamless user experience.


###3. Functional Requirements
1. Clean, Elegant User Interface

2. Organized Infrastructure of story choices

3. Maintain User Information throughout Session ( Health Points, Inventory, Location, Made Choices, Relationships )

4. Customizable Character

5. Minigames

6. New Game Plus


###4. Non-Functional Requirements
1. Must look appealing, immersive, and sellable to our audience

2. Must work on Android OS and Apple IOS

3. Bug Management

4. Updates based on user feedback

5. Smooth and Intuitive GUI

###5. MVP
For creating our MVP our main strategy will be to reference our interviews and observe overlapping opinions for deciding what to implement. Frequent specifications about important aspects in the game will be key to our MVP. Things such as smooth and intuitive UI as well as story immersion are common themes in all of our interviews thus far and are considered important to our MVP.
More interviews may be necessary to get a larger amount of opinions regarding features. With the current focus being on the user interface and the story, we will plan to develop the UI first for demoing and testing.


###6. Use Cases
#####a. Use Case Diagram
#####b. Use Case Description
*Elijah's Use Case*

######**Use Case: Test Game**

I. Brief Description: The use case demonstrates how the testers find bugs in the game & how the developers deal with said bugs

II. Actors: Testers & Developers

III. Preconditions: Game is still in development stage but is testable by testers

IV. Basic Flow of Events:

1. The use case begins when the game is being tested by the tester
2. Use Case: Play Game is performed by the tester
3. The tester performs every single action possible in a certain sequence in the game
4. If a bug is found, the tester then contacts the developers
5. Developers receives message about the bug
6. Developers communicates with the tester about the found bug
7. Developers talk within each other to debug it
8. Bug Fixed
9. Go to next sequence of action
10. Repeat step 3 ~ 9
11. Game tested successfully w/o bugs

V. Alternative Flows

1. No bug is found - in step #3, if no bug was found, skip to step 11
2. Cannot fix bug - in step #7, if the bug is not fixable, perform use case: Recode Game
3. Developers didn't receive message - in step #5, if testers somehow was not able to relay the message about the bug, go meet them physically 

VI. Key Scenarios

1. Game tested successfully w/o bugs
2. Game has game-breaking bug(s)

VII. Post-conditions 
Game tested successfully w/o bugs

*Vidal's Use Case*

######**Use Case: **
I. Brief Description:
II. Actors:
III. Preconditions: 
IV. Basic Flow of Events:
V. Alternative Flows:
VI. Key Scenarios:
VII. Post-Conditions

*Tommy's Use Case*

######**Use case: Wrong input**
I. Brief Description: This use case demonstrates how wrong inputs from the user will be handled.

II. Actors: Testers, Developers

III. Preconditions: Game is in development and misinputs/bugs are being smoothed out

IV. Basic Flow of Events:

1. Begin with game prompting for user input
2. User will input something to the game using implemented UI
3. The user inputs something that is invalid/doesn't make sense
4. Prompt is displayed notifying user of invalid input and must retry
5. User is brought back to previous screen where input is required again
6. User inputs valid option
7. Game continues as normal with users valid input.

V. Alternative Flows:

1. User correctly inputs from step #3, skip to step #6
2. User inputs incorrectly multiple times, repeat steps #2 ~ #5

VI. Key Scenarios:

1. User's wrong input is handled by simply prompting again for correct input
2. User inputs legal input from beginning

VII. Post-Conditions: User continues on through the game sequence


###7. User Stories

1. As a user, I want wrong inputs to be handled effeciently so that misclicks and typos will not drag on and be consequential to the story of the game. 
	a) We estimate this will take around 2 hours to fully implement

2. As a developer, I want constructive feedback about the story of the game so that I can create an immersive experience for users.
	a) We estimate this will be an ongoing piece of our game but may take ~20 hours or so

###8. Trello
https://trello.com/b/2S8T1pBG/cs-386-project-main
