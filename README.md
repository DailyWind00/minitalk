# minitalk ✅125/100
A simple server & client program

First use of the UNIX signals

- ![minitalk subject](fr.minitalk.subject.pdf)

The server display his PID and wait for a message to display from the client

The message is sent using only SIGUSR1 & SIGUSR2 as binary

![](client_binary_signal.PNG)

To use the programs, you must do these commands :
```shell
cd minitalk
make

# Program :

#  - Server
./server

#  - Client
./client <SERVER PID> <TEXT>
```

You also have these commands for cleaning the push_swap directory :
```shell
# Clean all object files (*.o)
make clean

# Clean static library & object files
make fclean

# Clean everything and recompile the static library
make re
```
