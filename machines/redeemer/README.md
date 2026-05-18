#Redeemer completed.

Redeemer is vulnerable because Redis had no password set. In production, Redis should always require authentication. Without it, anyone can connect and run KEYS * .
Cmds used, nmap -sV -p- --min-rate 5000 <ip> and then in redis, SELECT to select the database(0-15), and then KEYS * and finally GET.
