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
   `Normal output (-oN) with the .nmap file extension
    Grepable output (-oG) with the .gnmap file extension
    XML output (-oX) with the .xml file extension`
