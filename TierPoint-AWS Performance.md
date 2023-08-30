TierPoint >> AWS Performance

LOA
    - JumboFrame ordered?



JumboFrame
 - Included in LOA-CFA
 - ISP confirmed jumbo frames?
 - What is ISP configured MTU?
 - Wireshark MTU results
 - Switch MTU
 - AWS MTU
 - ESXi MTU
 - VM MTU

repeat for MSS

tierpoint diagram w/ 2 DX ckts and transit switches

AWS
    - 10Gig btwn VPCs?
    - IPSEC built via AWS template?

Firewalls
    - MTU
    - Tunnel acceleration ala Linwood fw

Do we have a Megaport VXC? https://www.slideshare.net/DavidMcCullough10/megaport-enabled-aws-direct-connect slide 15



Shlomi latency & Israel office  = CRB09 to 172.22.17.60 was 89.6MB/s,, crb09 tp 172.22.17.60 was 17.6MB/s,, ping from crb07 to crb08 was 10ms,, ping from 172.22.17.60 to crb08 was 10 ms,, transfer from 172.22.17.60 to p\\fs01 was 441MB/s,, trans

172.19.72.45
crb07 is onprem DC  
crb06 is onprem in Parker
crb08 is AWS DC
crb09 is AWS DC




Goal Capture Wireshark PCAP from CRB07 and CRB08

Transfer large file from CRB07 to CRB08

1) Connect to CRB07
2) Install Wireshark
3) From Command Prompt issue the following commands
    - ipconfig /all
    - netsh interface ipv4 show subinterfaces
    - netstat -s
    - netstat -e
    - netstat -s | findstr Errors
4) Save Command Prompt results to a network share


Connect to CRB08
5) Install Wireshark
6) From Command Prompt issue the following commands
    - ipconfig /all
    - netsh interface ipv4 show subinterfaces
    - netstat -s
    - netstat -e
    - netstat -s | findstr Errors
7) Save Command Prompt results to a network share

8) Start Wireshark on CRB07
9) Start Wireshark on CRB08
10) Transfer the large file from CRB07 to CRB08
11) Take a screen capture of the transfer illustrating the transfer speed
12) Stop and save both Wireshark results to a network share








ahighlandVCM (MTU 1514) ping -l 9000 crb07 -n 50 resulted in 50sent, 41received, 9lost 18%loss.. another time saw 38% loss
ahighlandVCM (MTU 1514) ping -l 1500 crb07 -n 50 resulted in 50sent, 35received, 15lost 18%loss.. another time saw 30% loss
ahighlandVCM (MTU 1514) ping -l 1000 crb08 -n 50 resulted in no problem results
ahighlandVCM (MTU 1514) ping -l 9000 crb08 -n 50 resulted in all pings drop



Supporting URLs

https://www.linkedin.com/advice/1/what-benefits-drawbacks-using-jumbo
How to use jumbo frames in TCP
To use jumbo frames in TCP, you need to configure both the sender and the receiver devices to support the same frame size. You also need to ensure that all the intermediate devices along the network path support the same or larger frame size. You can use tools such as ping or traceroute to test the MTU of the network and detect any potential bottlenecks or problems. You also need to adjust the TCP maximum segment size (MSS), which is the largest amount of data that a TCP segment can carry. The MSS should be equal to the frame size minus the IP and TCP headers, which are usually 40 bytes.

When to use jumbo frames in TCP
Using jumbo frames in TCP can be beneficial for certain scenarios, such as transferring large files or streaming high-quality video or audio. However, using jumbo frames in TCP can also have drawbacks, such as fragmentation, compatibility issues, and increased complexity. Therefore, you should weigh the pros and cons of using jumbo frames in TCP and decide whether they are suitable for your network and application needs.


https://superuser.com/questions/32098/how-to-diagnose-local-nic-wired-losing-packets
