# Network-Packet-sniffing-using-c
analyzing a packet trace that contains Ethernet and IP packet headers as observed on an operational network.
USE UBANTU LINUX OS is requirement and internet also<br/>
step 1 :- goto source code compiled folder and see there are source code files<br/>
step 2 :- there is a file main.c<br/>
step 3 :- using linux open terminal window here and type command<br/>
$ sudo gcc main.c -o main<br/>
step 3 :- then to run the code type again second command<br/>
$ sudo ./main<br/>
step 4 :- now you code is running<br/>
step 5 :- now you have a shell for command that are mentioned there<br/>
-r tracefile<br/>
-s<br/>
-e<br/>
-m<br/>
-i<br/><br/>
step 6 : - you have a packet like that in log file<br/><br/>
***********************TCP Packet*************************<br/>
TCP Header<br/>
|-Source Port : 443<br/>
|-Destination Port : 57568<br/>
|-Sequence Number : 2732202218<br/>
|-Acknowledge Number : 3971416504<br/>
|-Header Length : 8 DWORDS or 32 BYTES<br/>
|-Urgent Flag : 0<br/>
|-Acknowledgement Flag : 1<br/>
|-Push Flag : 1<br/>
|-Reset Flag : 0<br/>
|-Synchronise Flag : 0<br/>
|-Finish Flag : 0<br/>
|-Window : 118<br/>
|-Checksum : 62640<br/>
|-Urgent Pointer : 0<br/>
DATA Dump<br/>
IP Header<br/>
TCP Header<br/>
Data Payload<br/>
