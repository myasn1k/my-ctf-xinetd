# my-ctf-xinetd

fast deploy pwn , using docker and ctf_xinted

```
#usage: ./deploy.py ProjectPath ExposePort LinuxVersion [timeout(120 for default, 0 to cancel timeout)]
./deploy.py pwn1 10001 ubuntu:16.04
./deploy.py pwn1 10001 ubuntu:16.04 60
./deploy.py pwn1 10001 ubuntu:16.04 0
```
