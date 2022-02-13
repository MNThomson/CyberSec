# Port 22 - SSH
**NOTE:** Usually a good idea to just ignore until more data is gathered.

## Bruteforce
Hydra Usage:
```
hydra -l user -P pass.txt -t 10 $IP ssh -s 22
```
