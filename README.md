# Computer Networks Project
A text based multiplayer Hangman game utilizing a TCP connection with multithreading. Allows two clients to connect with a server and play hangman together by alternating who is picking the word and who is guessing what the word is. 

## About
This Hangman game supports two clients who will alternate picking and guessing the word. The program facilitates the game by keeping track of the rounds and number of guesses and switches user roles when one of the players has one the round. Note that the server can handle multiple games of Hangman at a time. To add another game, simply run Client.java in two additional terminals.

## Installation
1. Clone the repository
```sh
git clone https://github.com/udvale/Hangman-Game.git
```
2. Navigate to the project directory
```sh
cd src
```
4. Compile and run the server
```sh
javac *.java
java Server.java
```
5. Run two Clients in separate terminals
```sh
java Client.java <SERVER_IP_ADDRESS> <PORT>
```
