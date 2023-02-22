# Proposal and Wireframe

The proposal and wireframe is where you will document your grand plans. Spend time making these documents highly detailed. Your efforts now will surely pay off in the future. A well crafted project proposal can be as beautiful to look at as the project itself!

To give you inspiration, [here is an example for a simple Bouncing Box game](https://docs.google.com/document/d/1ubnnmUoDmL8dRnHEKmAzpGwQTPHUW-R7dZt6pVjNSBc/edit#)

## Proposal

Your proposal must include four sections with further details below: 
1. user story / gameplay
2. A description of the visual game components 
3. The major data values used in the game
4. High level descriptions of the user events and timer logic 

#### User Story / Gameplay

- Describe the gameplay
- What are the conditions when the game begins?
- Does the game have an end? If so, what are the conditions for when it ends?

> **Example:** Bouncing box is a game involving a box and a board. The box moves horizontally across the screen, bouncing off of the left and right sides of these screens to change direction. When the user clicks on the box, it will speed up and the number of times the user has clicked on the box will be displayed on the box as the “score”. The game could be timed where the user has 1:00 to click the box as many times as possible.

#### Visual Game Components:

- What are the visual game components? Which are static and which are animated?

> **Example:** In Bouncing Box, the game components are the board and the box. The board is static while the box is animated.

#### Data

- What data will you need to manage each game component?

> **Example:** In Bouncing Box, the data values for the box are `positionX`, `direction`, and `speedX`, and we’ll have separate variables to keep track of the `points` and the `secondsElapsed`

#### Events / Logic

- What events will occur in this game? (timer events, keyboard events, clicking events?)
- How do those events affect the data of the program?
- For each "event", write out the high-level logic of what will happen. It is better (and tricky) to be as specific as you can while remaining high-level!

> **Example:** When the box is clicked: the speed is increased; the point total goes up by 1; the new point total is displayed on the box; the position of the box is reset to 0. 
> 
> When the timer ticks: the box will be moved; we will check if it hits the wall and change the direction if it does; we will check if the timeElapsed has reached the limit and end the game if it has.

## Wire Frame

Your wireframe is where you will put to paper the ideas you have in your mind. Get creative here but make sure that you are meeting the bare minimum requirements.

- Different ways to wireframe
    - Use Google jamboard
    - Use google docs drawings/slideshows
    - White Board/Pen & Paper and take pictures
    - Figma
- Requirements
    - Bare minimum:
        - 3 In-game states shown (start state, mid game state, end state)
        - All visual elements are shown
        - Key of the visual elements describing their purpose
        - Animated elements have some indication of how they are animated (arrows showing movement or brief descriptions are fine)
    - Above and beyond:
        - separate UI for start and end game pages
        - clear design choices

Here are some examples from previous cohorts using Figma
* [Jungle Run](https://www.figma.com/file/9jqV6GdcpkFvoSgpBMuUgR/Untitled?node-id=0%3A1&t=3M7aZjsWtiIJVAvN-0)
* [Catching Apples](https://www.figma.com/file/dwPi9sx9glqNrYgB1DtbxR/Catch-the-Apples?node-id=0%3A1&t=1AT527ZvgS4gYCW4-0)