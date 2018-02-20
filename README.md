About:
This is a crap bit of python slapped together to save the world for my 
7 Days to die game.  Feel free to use it for whatever, but be warned- 
it is basic and not implemented with any exception catching, worries, 
or much of any cares.
Implementation:
This asks for a server, port, and password.  If no port is declared, 23 is used, and once all three are given, it will connect to the server, wait 5 seconds, enter the password, wait 5 more seconds, then start the loop.
The loop:
This loop is the stupidest thing ever, it is just outputting the command saveworld, then saying to the people on the server, saved, printing to console tick, and waiting 15 minutes from that time.  Rinse, repeat ad infinitum.  Only way out is ctrl-c because I am a lazy bum who wrote this up for me, not you.  Sorry.
