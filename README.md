[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=21149741&assignment_repo_type=AssignmentRepo)

# Reflection
Tons of things I've learned from this activity and I can't help but be amazed that an AI algorithm contains only a few lines for a tic tac toe game.
This is very interesting and I am willing to invest more time into learning these algorithms and how they work so in the future, I may be able to
create a program of my own which contains such AI algorithms.

## Insights
This gave me quite a bit of insights regarding how a game AI works and the efficiency of the algorithms used upon experiencing and doing it first hand and also upon adding counts and checking each algorithms time spent. Minimax has gone through a lot more nodes compared to Alpha-Beta which resulted in it consuming a bit more time than Alpha-Beta. This is pretty much as expected since Minimax evaluates every possible move to be made which resulted into either none of us winning or just me losing due to a mistake. Very powerful and intelligent algorithm. As for Alpha-Beta, it has a reduced number of nodes explored compared to Minimax and this is because of pruning which makes it avoid exploring parts that will never be chosen anyway. This is way more efficient and fast compared to Minimax as it reduces the amount of computation while not losing any accuracy. They pretty much have the same results with varied speed and efficiency. 

## Challenges
One of the challenges I encountered was examining the given code for both of the algorithms as I was unfamiliar about it. I still don't quite understand it by myself, I just knew the gist of it. With the help of AI, I tried to learn how each line of the algorithm works and how each line works together to make up the whole algorithm but even with that it was still quite hard to understand. Aside from this, I tried to think of more things I can try to track and measure in order to compare the two algorithms which took me a while but I ended up with nodes(given), time, and depth.
