#Redeemer completed.

The main problem here was we couldnt use default nmap, as the tcp port we were looking for was in higher range then 
1000, so we used specific flags, nmap -sV -p- --min-rate 5000, meanin show services and version, scan all the tcp
ports and speed up the scan.
