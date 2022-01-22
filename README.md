# Np-Course-project
Implement simple file server using sockets. The file server should be able to take the request from any client and return the requested file to client or return error message, status to client. Consider all the possible inputs for the file server. Implement using programming. Compare this result with FTP by using suitable tools.

1.Server
The server performs the following functions.

2.Start the program.

3.Declare the variables and structures required.

4.The socket is created using the socket function.

5.The socket is binded to the specific port.

6.Start listening for the connections.

7.Accept the connection from the client.

8.Creates a child process to handle request client among multiple clients.

9.Close server socket descriptor

10.Create a new file. 10. Receives the data from the client.

11.Write the data into the file.

12.The program is stopped.

13.Client
14.The client performs the following functions.

15.Start the program

16.Declare the variables and structures required.

17.A socket is created and the connect function is executed.

18.The file is opened.

19.The data from the file is read and sent to the server.

20.The socket is closed.

21.The program is stopped
