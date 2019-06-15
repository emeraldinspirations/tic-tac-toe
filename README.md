# Tic Tac Toe

The goals of this project are:
* Learn the basics of the Rust programming language
* Learn the basics of TDD in Rust
* Learn the basics of computer learning
* Learn `stdin` and `stdout` in a command line application

Steps to complete this project:
1. Render the playing board `ttt status`
2. Render the game in a specific state `ttt --state=156`
3. Retain the previous state and accept a move `ttt 7`
4. Enter an interactive mode `ttt`
5. Store the results of each game in a "memory" file `ttt --p1=p1.ttt`
6. Render the probability of a win in each move based on "memory" file
7. Create AI player using "memory" file `ttt --p1=p1.ttt --ai=p1`
8. Allow AI to play itself based on different "memory" files `ttt --p1=p1.ttt 
   --p2=p2.ttt --ai=both --gamecount=20`
9. Run all possible games
