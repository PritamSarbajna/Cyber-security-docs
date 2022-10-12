## Scan an entire network and see how many hosts are up :

```
nmap -sP 10.10.19.90/24
```

## To scan ports we specified :

```
sudo nmap -sT -p 80,443 10.10.19.90/24
```
