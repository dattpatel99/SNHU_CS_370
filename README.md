# SNHU_CS_370

1. Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

- The goal of this project was to train an AI agent to solve the given maze. The given code included the code for the Game Experience and the code file for playing the Treasure Maze. The Game Experience file had functions which could be used to remember episodes for Experience Replay, predicting the next action and getting input and target from memory. The Treasure Maze file including functions like getting reward, possible actions, drawing the game, updating game state, and etc. The code I created was for training the agent using Deep Q Learning. The code I created ran multiple episodes of the game until the win rate was 100%. From episode 100 onward the agent was trained as before that the game was played in an observation state so that more areas can be explored. After 100 episodes the agent began training by continuously do the following steps until the game was over. The agent would choose an action based on Epsilon-Greedy Algorithm, then it would perform that action, moving on it would remember the episode so it can be learned from using Experience Replay.

2. Connect your learning from throughout this course to the larger field of computer science:

- Through this course I was able to get a better understanding of the field of Computer Science. This course showed me how AI is being used in various things like analytics, security, hardware, and etc. Additionally, this course showed me how computer science is the study of using mathematics to implement calculations that mimic decision making. Finally, I learned how developing AI is similar to using math, data structures, and algorithms to indicate which decision is better than the other; which I think is like generic coding in Computer Science.

3. What do computer scientists do and why does it matter?

-	Computer Scientists work on creating solutions to problems. The problems can be as simple as making coffee faster and easier to as difficult as reducing reckless driving incidents using AI. Computer scientists are tasked with developing theories using mathematical functions such that the theories can efficiently assist in solving problems. For instance, a computer scientist working on AI would try and solve the problem of how a computer can think and make decisions similar to humans. The computer scientist would solve this problem by finding a way to implement human thinking in terms of math functions and convert that into theoretical functions which can later be implemented as code.

4. How do I approach a problem as a computer scientist?

-	My first step is to gather data on the problem and understand it better. Once I have a better understanding of the problem, I try to understand the final solution that I am trying to find. Doing so allows me to gain insights into what potential steps I would need to take to reach near that solution. Finally, I plan out the steps I am going to take to reach the solution and the research I will need to do.  

5. What are my ethical responsibilities to the end user and the organization?

-	There are many ethical responsibilities I have to the end user and organization but the one that comes to my mind first is to avoid harming others. Software and computers have been developed to assist in our daily lives not to cause harm to us. I think it is my responsibility to both users and organizations to ensure that malicious code is not used.
