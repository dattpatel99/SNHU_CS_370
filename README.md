# SNHU_CS_370

1. Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

- The goal of this project was to train an AI agent to solve the given maze. The given code included the code for the Game Experience and the code file for playing the Treasure Maze. The Game Experience file had functions which could be used to remember episodes for Experience Replay, predicting the next action and getting input and target from memory. The Treasure Maze file including functions like getting reward, possible actions, drawing the game, updating game state, and etc. The code I created was for training the agent using Deep Q Learning. The code I created ran multiple episodes of the game until the win rate was 100%. From episode 100 onward the agent was trained as before that the game was played in an observation state so that more areas can be explored. After 100 episodes the agent began training by continuously do the following steps until the game was over. The agent would choose an action based on Epsilon-Greedy Algorithm, then it would perform that action, moving on it would remember the episode so it can be learned from using Experience Replay.

2. Connect your learning from throughout this course to the larger field of computer science:

- Through this course I was able to get a better understanding of the field of Computer Science. This course showed me how AI is being used in various things like analytics, security, hardware, and etc. Additionally, this course showed me how computer science is the study of using mathematics to implement calculations that mimic decision making. Finally, I learned that in the field of computer science 

3. What do computer scientists do and why does it matter?

-

4. How do I approach a problem as a computer scientist?

-

5. What are my ethical responsibilities to the end user and the organization?

-
