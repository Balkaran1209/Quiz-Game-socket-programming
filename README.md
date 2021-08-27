# Quiz-Game-socket-programming
This is a socket based multiplayer(3) based on python

INSTRUCTONS

Open four terminals and run the following command on 1st Terminal:
python3 server.py
and run the following command on other three Terminals:
python3 client.py
I have used port 5006 so if it gives an error that the port is occupied, it can be changed simply by changing(in both client and server file) the port variable to any free port.
IP used is 127.0.0.1

This is a multiplayer game. The server has a list of 20 questions and it will randomly select the questions from the list. The asked questions are poped out from the list and are not asked again. The clients have to either press "y" (small y without quotes) or Y(capital Y without quotes) as the buzzer. The client that presses the buzzer first gets a chance to answer the question.
If the answer is correct then he gets +1 points and if the answer is wrong then he gets -0.5 points. The first user to reach 5 points is declared as winner. If no one presses the buzzer for 10 seconds, the server moves to the next question. The game ends when any of the user has earned 5 or more points and the user scoring 5 or more points is declared as the winner.

A set of instructions appear on the screen once the client connects to the server. A maximum of 3 clients can connect to the server at a single time.

BIBLIOGRAPHY

Computer Networking: A Top-Down Approach by Kurose and Ross
https://youtu.be/6jteAOmdsYg(complete playlist)
https://www.youtube.com/playlist?list=PLGKQkV4guDKEv1DoK4LYdo2ZPLo6cyLbm
https://www.youtube.com/playlist?list=PLQVvvaa0QuDdzLB_0JSTTcl8E8jsJLhR5
https://www.geeksforgeeks.org/simple-chat-room-using-python/
https://www.geeksforgeeks.org/sockets-python/
