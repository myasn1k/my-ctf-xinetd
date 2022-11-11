# my-ctf-xinetd

Fast deploy pwn, using docker and ctf_xinted.

- Note: must be run using bash

```
usage: ./deploy.py ProjectPath ExposePort [timeout(120 for default, 0 to cancel timeout)]
./deploy.py pwn1 10001
./deploy.py pwn1 10001 60
./deploy.py pwn1 10001 0
```
