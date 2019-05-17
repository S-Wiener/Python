# Simple Client/Server UDP Communication

For this program, there are two files: a client (UDPClient.py) and server (UDPServer.py), running on two different hosts. The client first sends a request for a movie to the server. The request packet contains the client's name, the name of the movie, and the time at which the movie should begin. Upon receiving the request, the server sends a response to the client containing the hostname of the server, the name of the movie, the cost for watching the movie, and an 8-bit integer which will serve as password for decoding the movie (simulated by RNG). Upon receiving the response, the client prints out the information it received to a client_log file. After sending the response, the server also prints out information to a server_log file

## Getting Started

Simply run UDPServer.py on a host, then run UDPClient.py on a separate host, after replacing the serverName and serverPort variables in both files with your chosen server..

### Prerequisites

* [Python](https://www.python.org/downloads/)
