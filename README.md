tryhackme notes
my pentesting notes and scripts
nmap basic scans
nmap -p 80 <target>
ping -c 4 10.66.177.68(THM server IP)
sends 4 ping packets only
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
sudo nmap -sX -p 1-999 --reason 10.66.177.68 
how many ports are open|filtered 
skip ping check -Pn infront of IP
NSE: nmap scripting engine, written in lua

safe,intrusive,vuln,exploit,auth,brute,discovery
nmap -p 80 --script=<scriptnmae> 
grep "smb" /usr/share/nmap/scripts/script.db
grep "safe"
TCP connect scans -sT, SYN half-open scans -sS, UDP scans -sU
should get RST if port not open.
syn scans need sudo.because syn needs the ability to create raw packets.
scanning with UDP us --top-ports <#>
nmap -sU --top-ports 20 <target>
-sV, -v -vv, save output of scan in three major formats.
ENUMERATION: start from zero. what do you know. what can you find out.
 
