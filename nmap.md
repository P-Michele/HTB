## General nmap Command

- To perform a service version detection and run default scripts against a host:
```
sudo nmap -sV -sC -oA nmap/out IP -vv -n
```
- `-sV`: Probe open ports to determine service/version info.
- `-sC`: Run default scripts.
- `-oA`: Output in all formats to the directory `nmap/out`.
- `-vv`: Increase verbosity.
- `-n`: Do not resolve DNS.


# Devices Scan
```
namp -sn <NET_IP>
```
It map (only) the devices in the network (no port scan) 
