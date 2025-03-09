# LookUp
Enumeration commands

nmap -p-
nmap -sC -sV -p 22,80
nmap -sS -p- -T4 -v -sC -sV -oA scan 10.10.33.43 

gobuster dns -d 10.10.33.43 -w /usr/share/wordlists/dirb/big.txt
froxbuster -u 'http://lookup.thm'  -w /usr/share/wordlists/dirb/big.txt



