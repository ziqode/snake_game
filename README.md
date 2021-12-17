
🅂🄽🄰🄺🄴 🄶🄰🄼🄴
ASCII title from: https://fsymbols.com/text-art/


A simple snake game I learnt as part of the bootcamp from Dr Angela of Udemy.
Code mainly focus around the idea of using the Turtle module. 

Main.py

- Create the game map
- Determine how the player will lose via wall collision and tail collision

Snake.py

- Create the snake
- Snake start of with 3 blocks according to the 3 positions given.
- Determine the distance(speed) of the snake.
- Snake to extend(add block) after each consumption of snack(add segment)
- Snake to reset to the initial 3 blocks and at the start position.
- Create the movement function 

Snack.py

- Create snack at random position
- Random position given is limited to -280,280 so as to not refresh in the scoreboard area.
- Snack will refresh as random color based on the given list in COLORS

Scoreboard.py

- Create scoreboard
- Function created to save highscore

