# Project - Hex game

---

101804 - Advanced Machine Learning

Laurea Magistrale - Computer science

Artificial Intelligence Track

University of Genova

---

Instructors:

- Noceti Nicoletta
- Rosasco Lorenzo
- Barla Annalisa
- Verri Alessandro

---

Student: Arnaud Ruymaekers

---

In this project, I explore building an Agent able to play the board game Hex.

Hex is 2 player where the goal is to link it's assigned two sides of the field. On interesting challenge about this game is that, due to the hexagonal architecture of the grid, there will always be a winner and a looser, there is no ties. It is usually played on a 11 by 11 or 13 by 13 board, which is a state space larger than the one of chess.

I explore the building of the agents we built in class to this board-game. I first build a trivial random play agent that is used to play against other agents. Following this I build a Minimax Agent with a limited search depth. Then, getting into reinforcement learning, I build a TQ-learning agent. And finally I build a deep-Q learning agent.