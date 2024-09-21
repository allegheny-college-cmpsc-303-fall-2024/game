# Project 1:  Game

For your first self-directed project in Artificial Intelligence, you will create a game of your choosing. You can invent a game, or go with a classic.

You should use techniques learned in class so that you can play your game against the computer if it is a multi-player game, or so the computer can find an optimal solution if it is a single-player game. 

This assignment builds toward CLO #1 (implementing an intelligent agent) and CLO #2 (applying search algorithms), CLO #3 (designing AI systems) and CLO #5 (communicating outcomes). You can read more about CLOs [here](https://github.com/allegheny-college-cmpsc-303-fall-2024/course-materials/blob/main/README.md#course-learning-outcomes). 

> [!IMPORTANT]
>
> Late work will not be accepted unless you [apply a token](https://docs.google.com/forms/d/e/1FAIpQLSefo2mnYhrX1h6TB6kZvhu1SCYY7H2CMK0BtuorrpMojqqKnQ/viewform?usp=sf_link) at least 24 hours before the deadline. You get two tokens in this class: one that can be applied during the first half the semester, and one that can be applied during the second half of the semester. 

The final deadline for all steps is October 22. Intermittent deadlines are as follows:

| Doc                                        | Steps                                                        | Deadline    |
| ------------------------------------------ | ------------------------------------------------------------ | ----------- |
| [`docs/plan.md`](docs/plan.md)             | Complete TODOs                                               | 9/30        |
|                                            | Sign up for a presentation slot at [this link](https://docs.google.com/spreadsheets/d/1GzT5MQK5CpK2jyGcnZU0H9MJ0zwiMazMtKAd_yxZZWs/edit?usp=sharing) | 9/30        |
| [`build/main.py`](build/main.py)           | Create your working game in this file. (You are welcome to add additional files in the `build` directory and use them in `main.py` as needed) | 10/17       |
| [`docs/reflection.md`](docs/reflection.md) | Complete TODOs.                                              | 10/21       |
|                                            | Presentations                                                | 10/22-10/24 |

If you miss an intermittent deadline, your assignment will still be accepted as long as you complete all work in your repo by the October 21 deadline. However, missed interim deadlines may result in a grade reduction. 

## Resources

- [Class slides](https://drive.google.com/drive/folders/1nnPXaz3lpiarqAO2kBn2tA9wEFOimALW?usp=drive_link)
- [Class repositories](https://github.com/orgs/allegheny-college-cmpsc-303-fall-2024/repositories?q=visibility%3Apublic+archived%3Afalse)
- [CS50 AI | Search](https://cs50.harvard.edu/ai/2024/weeks/0/)

## Grading

> [!NOTE]
>
> This assignment is primarily human-graded. Gatorchecks, if available, may help you confirm that you have completed certain objectives, but they do not necessarily reflect your grade. 

To receive a satisfactory grade on this assignment, you should complete all of the following checkmarks: 

- [ ] Complete all TODOs in `docs/plan.md`

- [ ] In the `build` directory, create a game that either allows the player to compete with your program, or shows your program finding an optimal solution to a single-player game. This solution should involve the use of a search algorithm. 
- [ ] The program's output should give a clear idea of game play. You can make an animated gameboard or screen. At a minimum, the game should output text to Terminal.
  - When you run `python build/main.py` the game should play smoothly, including clear instructions for the user as appropriate. 
- [ ] Use one technique that was shown or mentioned in class, butnot explicitly tested in any of the challenges. This is so that you can learn how to research and deploy code techniques on your own. These techniques include:
  - A* search
  - MiniMax optimization/alpha-beta pruning
  - Animating an interactive gameboard in `pygame` or another Python library. 
- [ ] Complete all TODOS in `docs/reflection.md`
- [ ] Share your game with the class. 
