Chess is a two-player strategy board game played on an 8 × 8 checkered board with 64 squares. The history of chess can be drawn back to around 1500 years, it was started in the North of India and spread throughout the world. Each player begins with 16 pieces one king, one queen, two rooks, two knights, two bishops and eight pawns. Each type of piece moves uniquely of which the most powerful is the queen and the least powerful is the pawn. Although the rules of the game have been amended multiple times the main objective is to checkmate the opponent’s king by placing it under an inescapable threat of capture. The invention of databases and chess engines in the 20th century revolutionized chess.

The goal of the project is to predict the number of moves (from 0-16) required to win for white with a king and a rook, given the position of white king, white rook and black king. It is a multiclass classification problem. The dataset has 28,056 rows and has the following attributes 
1. White King file (column)       - X1
2. White King rank (row)          - X2
3. White Rook file 	          -X3
4. White Rook rank 	          -X4
5. Black King file 		  - X5
6. Black King rank 	          -X6
7. optimal depth-of-win for White in 0 to 16 moves, otherwise drawn {draw, zero, one, two, ..., sixteen}.			  -Y	

As a team we are fascinated with the game. The rich history and the complexity (10 to the power 120 games possible) of the game dragged us to this project. The chess Engine came to limelight when deep blue, IBM Engine beat Garry Kasparov (in year 1997) the Russian Grand Master and world champion at that time. After that chess Engines took a huge turn and engines like stock fish were developed which is based on brute force algorithms. 

In late 2017 Google developed an AI based chess Engine which learned the game, in just 4 hours playing with itself and beat stockfish8. We got inspired by the engines and how they evolve that is why we want to explore this dataset.
