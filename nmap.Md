## Scan IP list
 `-iL	Performs defined scans against targets in provided 'hosts.lst' list.`

## Scan for only IP
 `-sn	Disables port scanning.`

## ICMP echo request
 `-PE	Performs the ping scan by using 'ICMP Echo requests' against the target.`

## Disable ARP ping method
 `--disable-arp-ping`

## Top ports scan
  `fast port scan which contains top 100 ports (-F).`
  `--top-ports=10	Scans the specified top ports that have been defined as most frequent.`
   
## Clear view of SYN scan
  `To have a clear view of the SYN scan, we disable the ICMP echo requests (-Pn), DNS resolution (-n), and ARP ping scan (--disable-arp-ping).`

## Connect Scan
 `Nmap TCP Connect Scan (-sT) uses the TCP three-way handshake to determine if a specific port on a target host is open or closed.`

## Saving the outupt
   `Normal output (-oN) with the .nmap file extension`
   `Grepable output (-oG) with the .gnmap file extension`
   `XML output (-oX) with the .xml file extension`

## Performance

We can use various options to tell Nmap how fast `(-T <0-5>)`, with which frequency `(--min-parallelism <number>)`, which timeouts `(--max-rtt-timeout <time>)` the test packets should have, how many packets should be sent simultaneously `(--min-rate <number>)`, and with the number of retries `(--max-retries <number>)` for the scanned ports the targets should be scanned.
`--initial-rtt-timeout 50ms` 	Sets the specified time value as initial RTT timeout.

## Decoy

`-S` Source IP Address Spoofing

`-e` Specify Network Interface

`-D` Decoy Scanning

`-g`	Specifies the source port for the scan.

## DNS Proxying 

`--dns-server` Custom DNS Servers 

`--source-port` Source Port Manipulation 
