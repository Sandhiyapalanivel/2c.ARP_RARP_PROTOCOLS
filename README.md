# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![Screenshot 2024-09-30 142318](https://github.com/user-attachments/assets/a35cc7b8-20ee-497a-840b-ea0cfe56c48a)

## OUPUT - ARP
![2cout](https://github.com/user-attachments/assets/d475d36f-2b4e-4389-bd6c-ccb54d767aed)


## PROGRAM - RARP
![image](https://github.com/user-attachments/assets/7ee46ba5-a37c-4b6d-80c2-23b1b9b1771c)

## OUPUT -RARP
![image](https://github.com/user-attachments/assets/3fe86edf-d38d-46f9-82a8-a7abedad8084)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
