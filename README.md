# Chess-Game
An AI based Chess Game using Alpha-Beta Pruning

## Goal
The main goal is to find the best move in a given chess position. The output is in the following format i.e piece name + square it should move. For example, KingD1 (king moves to square D1) and QueenF3 (queen moves to square F3).

## How the Selection Algorithm Works 
1.   Uses minmax-tree algorithm based on decision tree for decision making
2.   Alpha Beta Pruning is used to prune the tree 
3.   After pruning it traverses that tree, evaluates the highest ranked move and sends it as a list.
4.   The depth of the decision tree is 3.

## Analysis of Computer vs Computer
Number of Moves = 60
Winner = Draw(by repetition)

Analysing the entire game, the code was efficient enough to track the opposing players moves, it was successful enough to capture most of the opposing players' pieces, as well try to find a way to encounter the king. Our accuracy according to chess.com was 24.3, while the opposing player had 14.4.