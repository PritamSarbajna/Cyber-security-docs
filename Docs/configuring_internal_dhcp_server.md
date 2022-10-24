## Step #1

```
cd /Program Files/Oracle/VirtualBox
```

## Step #2

```
vboxmanage dhcpserver add --network=NETWORK_NAME --server-ip=10.38.1.1 --lower-ip=10.38.1.110 --upper-ip=10.38.1.130 --netmask=255.255.255.0 --enable
```
