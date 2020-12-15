# Reverse shell w/ Remote code execution

Reverse Shell with remote code execution written in python using sockets. Allows the attacker to execute native commands on the victim's machine remotely.

### Features
* Reverse connection
* Remote code execution

### Anti-Features
* Not compiled

### Bugs
* Change directory "__cd__" command crashes the program.

## How to run
> * set HOST = '[attacker's IP address]' in both client.py and server.py.
> * execute server.py on attacker machine.
> * execute client.py on victim machine.

extra
>* compile client.py for professionalism.

caveat: obligatory, I DO NOT take resposibility for misuse of this script. This script is for educational purposes only.
