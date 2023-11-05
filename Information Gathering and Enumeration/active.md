# Active Information Gathering

- nmap
	- Host Discover:
 		- `nmap -sn <ip_address>/<CDIR>`
   	- Port Scan:
   		- 
- netdiscover
	- `sudo netdiscover -i eth0 -r 192.168.2.0/24`
- For doing DNS zonetransfer: `dig axfr <nameserver> domain`
	- `dig axfr @nsztm1.digi.ninja zonetransfer.me`
- fierce
	- `fierce -dns zonetransfer.me`
