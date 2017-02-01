# NTAL
NTAL project for Remote Backdoor Shell using Python

To perform the remote backdoor shell implementation, we assume that an attack has already taken place for the purpose of this project. After the attack a backdoor python shell code is left behind on the victim's PC. This code is the server side code that acts as a backdoor in the infected PC. 
The Server code is what runs on the victim’s device in the background. The server is essentially a basic, lightweight HTTP Server to which the attacker will send commands in the form of requests. This should allow the data flow between the attacker’s device and the victim’s device to be obscured with the rest of the web traffic that might be going through the victim’s device. The Server code accepts a request from the attacker, parses it and runs the appropriate method.
Ideally, this code should be silently running in the background, but the below code has been made verbose for the purpose of the project documentation.

Project members:
Asha Anthony
Jacques Fernandes
Nischal Abraham
Alisha Cheyaden
