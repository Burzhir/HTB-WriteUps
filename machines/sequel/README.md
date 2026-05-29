#Sequel completed

Used nmap -Pn -sV -T2 --min-rate 5000, and then saw its runnin mysql on port 3306, so used nmap --script mysql-info, mysql-enum, to get detailed info and logged into using mysql -h <ip> -u root--ssl=0, MsriaDB is maybe runnin older ver, unsupported, thats why --ssl=0, got access after using root for username, gainin access without password, inside sql terminal, used, 'show database;' to gain info bout them, used 'use <database>;', to select then 'show tables;;\' then 'select * from <name>', inside, captured the flag.
