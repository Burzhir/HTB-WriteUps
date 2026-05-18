#Redeemer completed.

Redeemer is vulnerable because Redis had no password set. In production, Redis should always require authentication. Without it, anyone can connect and run KEYS * .
