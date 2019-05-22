# Socket Client Server Messager
Send a string by socket connection using Client and Server

## Getting Started
This repository provides a simple aplication that uses socket connection to send a string by client and Server, using C/C++ language.

### Prerequisites

  - SO -> Linux Ubuntu
  - Programming Language -> C/C++

### Run Server
Create a simple socket server, to print a message sent by client.

- 1: Using the terminal enter in repository **/server** folder and type the command:  
```c++
make clean
make
```
- 2: To run, type in the terminal:
```c++
./server.o
```
### Run Client
Create a simple client socket connection, to send a message for server.

- 1: Using the terminal enter in repository **/client** folder and type the command:  
```c++
make clean
make
```
- 2: To run, type in the terminal:
```c++
./client.o <IP ADDRESS>
```
