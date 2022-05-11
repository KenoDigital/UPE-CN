# PROCEDURE:  
## CLIENT SIDE
1. Start the program
2. using datagram sockets UDP function is established.
2.Get the MAC address to be converted into IP address.
3.Send this MAC address to server.
4.Server returns the IP address to client..
## SERVER SIDE
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are stored.
4. Read the IP address which is sent by the client.
5. Map the IP address with its MAC address and return the MAC address to the client.
