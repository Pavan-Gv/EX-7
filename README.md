# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND
```
DATE : 20-04-2023
```
### AIM :
To write the python program for simulating Traceroute command.
### ALGORITHM :
```
1.Start the program.
2.Get the frame size from the user.
3.To create the frame based on the user request.
4.To send frames to server from the client side.
5.If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
6.Stop the program
```
### PROGRAM :
```
Developed by : G Venkata Pavan Kumar
Register Number : 212221240013
```
```
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
### OUTPUT :
![image](https://github.com/Pavan-Gv/EX-7/assets/94827772/a1ac91f5-3f58-4160-844e-737ca0a10d92)
### RESULT :
Thus, the python program for simulating Traceroute command was successfully executed.
