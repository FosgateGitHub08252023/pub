Misc

Dentist fri 11:30



Palo Alto Network GlobalProtect from Azure's Enterprise Applications
SAML
Entity ID is vpnlinwood.crbnj.net 131.239.170.97

Identifier (Entity ID)
https://vpnlinwood.crbnj.net/SAML20/SP

Reply URL (Assertion Consumer Service URL)
https://vpnlinwood.crbnj.net/SAML20/SP/ACS

Sign on URL
https://vpnlinwood.crbnj.net

Download and send me the Base64 cert and the Federation Metadata XML


^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Thales IPs - brian asked me to send them to you.
 
cm01.crbcloud.com [172.22.10.105]
cm02.crbcloud.com [172.22.10.106]

its 2 node cluster, .105 is primary

hey, here are the thales appliances ports. From TierPoint
 
TEK
crossriverba-tek-sw0#show run inter Et45
interface Ethernet45
description [cus] crossriverba-tek-thales01 [LOM 1]
shutdown
speed forced 10000full
switchport access vlan 201

crossriverba-tek-sw1#show run inter eth45
interface Ethernet45
description [cus] crossriverba-tek-thales01 [LOM 2]
shutdown
speed forced 10000full
switchport access vlan 2010

VFO
crossriverba-vfo-sw5(s1)#show run inter Et5/42
interface Ethernet5/42
description [cus] Thales HSM Appliance Port 1
shutdown
speed forced 10000full
switchport access vlan 2010
crossriverba-vfo-sw6(s1)#show run inter Et5/42
interface Ethernet5/42
description [cus] Thales HSM Appliance Port 2
shutdown
speed forced 10000full
switchport access vlan 2010



^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

58fDFe3Ki754654fSSFWe0z63542 from RS2

CRB Merchant Portal: https://crb-portal.bw-sp.com/generic-module-loader/ui/warp/index.html{}   has been whitelsited... 

98.109.107.96
255.255.255.0
98.109.107.1

berryl fiserv 

PROD UI URL: https://bankworks.bw-sp.com/bw1/bankworks/signon.cfm#/  requries an IPSEC VPN


Teva/Tahvah
Uriel/ Oh-re-el

[9/18 11:12 AM] Deborah Garfinkel

We have 5, starts at .92 with gateway at .1.... 98.109.107.1

131.239.170.90/29 > 131.239.170.89 – 131.239.170.94  All IPs are used except for 131.239.170.91 and 131.239.170.94
131.239.170.97/27 > 131.239.170.97 – 131.239.170.126 All IPs are free
131.239.170.125 will be guest wifi

1gb file download from testfil.org took 23 secs on my home network

>>>>>>>>>FedNow<<<<<<<<<<<<
show routing fib virtual-router VR1
273     10.96.0.0/11          VR_AWS             u      VR1/i3             0   
10.96.0.0/11 = 10.96.0.1 - 10.127.255.254

( addr.dst in '10.104.131.238' ) and ( addr.src in '172.22.16.72' ) and ( interface.dst eq 'tunnel.17' )

Fednow_Dev = 170.209.237.12
172.122.110.5 is where we route to Fednow Dev

Fedline_Fednow_Test_Source = 172.22.112.30

AWS_COS_NonProd
  AWS_COS_Dev_10.100.0.0 = 10.100.0.0/16
  AWS_COS_QA_10.101.0.0 = 10.101.0.0/16
  AWS_COS_Sandbox_Dev_10.103.0.0 = 10.103.0.0/16
  AWS_COS_UAT_10.102.0.0 = 10.102.0.0/16


Fednow_Prod = 170.209.237.2
172.122.110.5 is where we route to Fednow Prod

Fedline_Fednow_Prod_Source = 172.22.112.31 was this
Fedline_Fednow_Prod_Source1 = 172.22.112.31
Fedline_Fednow_Prod_Source2 = 172.22.112.32
Fedline_Fednow_Prod_Source3 = 172.22.112.33
Fedline_Fednow_Prod_Source4 = 172.22.112.34

AWS_COS_Prod_App_All
  AWS_COS_Prod_App_Subnet1 = 10.104.30.0/23
  AWS_COS_Prod_App_Subnet2 = 10.104.130.0/23



westly see no fednow connections at VFO ATM. he only sees fedline advantage connecting to VFO, no
should we see contstant traffic 

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Parker
ISP1: 108.5.146.234
ISP2: 69.193.205.123

VFO
ISP1: 144.202.179.228
ISP2: 66.206.202.202


PC_Amichai_Lichtenstein
172.22.16.123 is in Developer_VMs_VF
192.168.165.108 is in IT_Devel_PCs
app openai-chatgpt


SFP-1G-T-AO

\\\

EmpMngUat01 = 172.22.45.100
172.22.119.0/24 i.e 172.22.119.2 (DMZ_L3)
Server_CRBTFS01 = 192.168.145.12

\\\
"I'm sorry, that Allahu akbar makes my skin crawl!" - Megyan Kelly

Alexander Grillo, Simon Lee, Bora Lee and Anthony Biondo?

( addr.dst in '170.209.237.2' ) and ( time_generated geq '2023/10/10 00:00:00' ) and ( time_generated leq '2023/10/11 03:00:00' )


cn=secinternalauditdepartment,ou=security groups,dc=crb,dc=local
cn=secAWSSnowFlakeAccess,ou=security groups,dc=crb,dc=local
cn=seccloudstorageallow,ou=security groups,dc=crb,dc=local

cn=secSASVIExternalAudit,ou=security groups,dc=crb,dc=local

[2:11 PM] JSH Adil Raza

Alex Grunstein and  and Anne Walton also require access
Andi Choyce, Majilinda Qarmarani, 

 ( user.src eq 'crb\araza' ) and ( addr.src in '172.16.164.138' )

crb\secCloudflareOps
PC_Amichai_Lichtenstein = 192.168.165.108
PC_Amichai_Lichtenstein_VF = 172.22.16.123

crb\seccloudstorageallow
crb\secAWSSnowFlakeAccess

clear dhcp lease all
debug software restart process dhcp

GP cert pwd: fBR6#RLesoD^qyK

we are missing the private key

192.168.165.46  b0:7b:25:06:32:16                                   reserved  kschierle2pc

131.239.170.88/29 = 131.239.170.89 – 131.239.170.94
131.239.170.96/27 = 131.239.170.97 – 131.239.170.126

NAT - in security policy, use pre-NAT destionation IP and post-NAT destionation zone

with regards to FiOS internet, the linksys has 5 ports, all 5 ports are lit. 2 go to fios, 2 go to fws and one to eth0 of savecom router; then port eth2 of savecom goes to port 1 of linw v 4-1 switch




ToDo
Disable split-tunnel
Remove LinkSys and devices unable to send logs, support NAC
Ignore tgw-tch-vpn-rt01 in Transit gateway route tables
fix teaneak branch logs
monitor brooklyn fw in SW


AWS Direct Connect > Connections = dxcon-fgjpqw2d
WS Direct Connect > Virtual interfaces = dxvif-fgj87vog
Direct Connect > Virtual private gateways = vgw-0164500cee72423c1
Direct Connect > Transit gateways = tgw-0a7d8c2374fcde4bd

crb_customer_dx_gateway  cgw-01e25a3156bd2a370	65000	69.210.70.91  vpn-016a24dad9ea49f17	–	tgw-0a7d8c2374fcde4bd	69.210.70.91 Static Tunnel 1	35.174.70.10	169.254.85.176/30 && Tunnel 2	52.3.65.116	169.254.105.96/30

crb_customer_vpn_gateway cgw-04f8837a3a33d05e7	65000 AWS-VPN-CRB-Secondary vpn-0464275f80f564308  tgw-0a7d8c2374fcde4bd  66.206.202.202 Static  Tunnel 1	3.209.246.40	169.254.220.208/30 && Tunnel 2	54.152.170.204	169.254.168.212/30


@megynkelly @patrickbetdavid @dbongino @nytimes @elonmusk @UNICEFUSA @UN @WHO @WSJ @washingtonpost @nypost @DonaldJTrumpJr @joerogan @bennyjohnson @CNN @wolfblitzer @BarackObama @FoxNews @maddow @TuckerCarlson @Cobratate @alexandracooper @BarstoolRadio @hubermanlab @NPR

#GazaGenocide #gazaholocost

"You can kill a revolutionary, but you cannot kill a revolution" - Afeni Shakur #FreePalestian #CeasefireNOW #WeAreTheWorld

CRB.LOCAL Domain Controllers: is DCs_crb.local in PA
172.16.64.55 = CRB09.crb.local
172.16.64.45 = CRB08.crb.local
192.168.65.5 = CRB06.crb.local
172.22.20.5 = CRB07.crb.local

CRBCLOUD.COM Domain Controllers: is DCs_crbcloud.com in PA
172.22.19.5 = CDC01.crbcloud.com
172.22.19.6 = CDC02.crbcloud.com
172.16.64.10 = CDC04_AWS
172.16.64.20 = CDC05_AWS

CRB.AWS Managed AD Domain Controllers:
172.16.41.191
172.16.23.187

DCs_crbcloud.com included CDC03_DA (172.28.14.5) but his request did not include CDC03_DA
DCs_crb.local includes CRB02_DA (172.28.14.10) but his request did not include CRB02_DA

DNS_to_DCs and DCs_Access might need to be updated but that would include users

CRB_Active_Directory covers the ports



o   TCP 636 – LDAPS (LDAP over TLS/SSL)

o   TCP 3268-3269 – Global Catalog

o   TCP 1024-65535 – Ephemeral ports for RPC

o   ICMP – All

Comments for ticket
What are hostnames for the two CRB.AWS Managed AD Domain Controllers?

200k 
300 miles 80mph charge 3times each charge was $20 he drove 400 miles

surveyd and reviewd Linwood firewalls. ready to stage the cutover to old Linwood firewalls to the new linwood firewall. waiting for r/w access

P2P

SOC FW Change Group

I can ssh to the Parker FW @ 192.168.143.16
ForLee_Parker is Parker Plaza's Device Group



MS250-48 Layer 3 switch with optional PoE+
MS350-48 Layer 3 switch with optional PoE+


I'll prep the fw for israel firewall

reviewing the VFO to AWS connectivity
MegaPort details and need to followup with them with addiation questions
Sholmi performance  - - - reviewing the VFO to AWS connectivity

israel office diagram
  need number of floors
  number of ports per floor
  floor plan

ip.src == 54.209.197.230 and ip.dst==66.206.202.41 and tcp.srcport==49642

received by fw < leave>
transmitted from fw
dropped by fw

Ticket number: 
taylor
kristin

tcp.dstport == 443 or tcp.srcport == 443

!(tcp.dstport == 80) and !(tcp.dstport == 23)

Understand WAN
    - P2Ps
    - IP Layout
    - VLAN Allocation
    - AWS VPC networking

    Select TCP row
    click Transmission COntrol Protocol
    Click Timestamps
    Right click Time since previipreviousus frame in this TCP segment } Select Apply as a column | Call it TCP Delta
    Sort the TCP Delta cloumn then click the green arrow
    Select Conversation Filter TCP
    Select # column to put packets back in order.



Add NetOps@crossriver.com to the following;
From: no-reply@megaport.com
From: sre@crossriver.com w/r/t [SRE Ticket #543223] FW: ALARM: "Tunnel is_Down" in US East (N. Virginia)
From: NOC@crossriver.com w/r/t FW: ALARM: "Tunnel is_Down" in US East (N. Virginia)
From: noreply@notifications.newrelic.com   Monitor failed for location CRB AWS on 'Arix Prod - Loan Creation - AWS' - Issue 1723e47b-f8fd-4d49-8c92-5308997b187b ?? not sure if I should add this. Review before requesting
From: CRB Monitoring System <noreply@crossriver.com>  Weekly Switch Report
From: no-reply@lumen.com Lumen Ticket #: 27560189, CRB GROUP, INC-5-2BC7ZBPC, Ticket Opened, Customer Ticket ID:
From TierPoint IT Help Desk <support@tierpoint.com> i.e Subject: TierPoint Maintenance Notification - Multi-site - Commvault Backup Infrastructure Maintenance (DBSI CommCell)

Who/what is the MerakiTeam (MerakiTeam@crossriver.com)?



540644

6pmwFpMt.K!ZiBTr]y#z]
6pmwFpMt.K!ZiBTr]y#z]

https://www.amazon.com/Surprise-Surprises-Accessories-Limited-Collectible/dp/B0B9CG3LJ3/ref=sr_1_6?crid=36H83AOQFAITZ&keywords=lol+dolls+surprise&qid=1692382601&sprefix=lol+dolls+%2Caps%2C105&sr=8-6


/Users/ahighland/Library/CloudStorage/OneDrive-CrossRiverBank/Apps/VanDyk3/SecureCRT/Config/L0GFIL3/%M%D%h%H%S.log

https://online.roboform.com/login?relogin
ahighland@crossriver.com

ph+472312
Teaneck1

FG-90G-BDL-950-12  = 2,850.90
Palo Alto Networks PA-460 - security appliance = 5,191.99



Resolution
Incomplete in the application field:

Incomplete means that either the three-way TCP handshake did not complete OR the three-way TCP handshake did complete but there was no enough data after the handshake to identify the application. In other words that traffic being seen is not really an application.


fiserv jeremry


Admin_Pcs

7543 9267
adminali

Password123!

192.168.44.87 = de:22:a6:3b:b8:ca

google-drive-web saas (Category) file-sharing (subcategory)

rule 1457 of VFO shows Default_All)Out with User Any allows to google-drive-web.. crb\ryoo crb\jfinkelstein, crb\daki

just checked 3260-FortLee-A and saw no google-drive-web allows
Checked PA-460-Linwood-A and saw 

Google_Drive_Allow is rule 61
Google_Drive_Banned is #88 in Linwood

palo alto Ali_Highland_785

Ali_Highland_8

online-storage-and-backup




onprem to onprem was 200-300MB/s same file 
VPC to VPC was 110MB/s same file but said he would see 500MB/s
300avg btwn AWS DCs is what he remembers


was hitting 80MB/s over one tunnel but 40MB/s over two tunnels

public interenet is 2gig is kbps

shlomi


crossriverba-tek-sw0
crossriverba-tek-sw1
crossriverba-tek-mgmt-sw0  << enable lldp
crossriverba-vfo-sw5
crossriverba-vfo-sw6 
crossriverba-vfo-mgmt-sw0



]]]]]]]]]]]]]]]]]]]]]]]]
]]]]]]]]]]]]]]]]]]]]]]]]
]]]]]]]]]]]]]]]]]]]]]]]]


LIN-01-TRNS-SW-01(s1)#sh run
!
terminal length 25
!
errdisable recovery cause bpduguard
!
ntp server____________ prefer
ntp server____________
!
logging buffered notifications
logging monitor notifications
!
hostname LIN-01-TRNS-SW-01
!
ip name-server vrf default 208.67.220.220
ip name-server vrf default 9.9.9.9
!
dns domain crb.local
!
spanning-tree mode rapid-pvst
spanning-tree vlan make fio primary here!!!!!!
spanning-tree  vkab 1-frio- prioruty 0......
no spanning-tree vlan-id 2000<<<>>>
!
VLAN 998
name ISP2
!
vlan 2000
   name MLAGPEER
   trunk group MLAGPEER
!
interface Port-Channel2000
   description To LIN-01-TRNS-SW-02
   logging event link-status
   switchport mode trunk
   switchport trunk group MLAGPEER
!
interface Port-Channel1999
   description LAG to FW-01
   logging event link-status
   switchport trunk allowed vlan 998
   switchport mode trunk
   mlag 1999
!
interface Port-Channel1998
   description LAG to FW-02
   logging event link-status
   switchport trunk allowed vlan 998
   switchport mode trunk
   mlag 1998
!
interface Ethernet11
   description E11 of FW-01
   logging event link-status
   switchport mode trunk
   channel-group 1999 mode active
!
interface Ethernet12
  description E12 of FW-02
   logging event link-status
   switchport mode trunk
   channel-group 1998 mode active
!
interface Ethernet47
   description E47 (MLAG) of LIN-01-TRNS-SW-02
   logging event link-status
   speed forced 100gfull?????
   switchport mode trunk
   witchport trunk group MLAGPEER
   channel-group 2000 mode active
!
interface Ethernet48
   description E48 (MLAG) of LIN-01-TRNS-SW-02
   logging event link-status
   speed forced 100gfull?????
   switchport mode trunk
   witchport trunk group MLAGPEER
   channel-group 2000 mode active
!
interface Vlan2000
   description <== MLAG Peerlink ==>
   no autostate
   ip address 100.127.255.253/30
!
ip routing
!
mlag configuration
   domain-id MLAG-DOMAIN-2000
   local-interface Vlan2000
   peer-address 100.127.255.254
   peer-link Port-Channel2000
   reload-delay non-mlag 240
!
ip route 0.0.0.0/0 172.22.16.1??????






]]]]]]]]]]]]]]]]]]]]]]]]
]]]]]]]]]]]]]]]]]]]]]]]]
]]]]]]]]]]]]]]]]]]]]]]]]


LIN-01-TRNS-SW-02(s1)#sh run
!
terminal length 25
!
errdisable recovery cause bpduguard
!
ntp server____________ prefer
ntp server____________
!
logging buffered notifications
logging monitor notifications
!
hostname LIN-01-TRNS-SW-02
!
ip name-server vrf default 208.67.220.220
ip name-server vrf default 9.9.9.9
!
dns domain crb.local
!
spanning-tree mode rapid-pvst
spanning-tree vlan make fio primary here!!!!!!
spanning-tree  vkab 1-frio- prioruty 0...... higher than 01
no spanning-tree vlan-id 2000<<<>>>
!
VLAN 998
name ISP2
!
vlan 2000
   name MLAGPEER
   trunk group MLAGPEER
!
interface Port-Channel2000
   description To LIN-01-TRNS-SW-01
   logging event link-status
   switchport mode trunk
   switchport trunk group MLAGPEER
!
interface Port-Channel1999
   description LAG to FW-01
   logging event link-status
   switchport trunk allowed vlan 998
   switchport mode trunk
   mlag 1999
!
interface Port-Channel1998
   description LAG to FW-02
   logging event link-status
   switchport trunk allowed vlan 998
   switchport mode trunk
   mlag 1998
!
interface Ethernet11
   description E11 of FW-02
   logging event link-status
   switchport mode trunk
   channel-group 1998 mode active
!
interface Ethernet12
  description E12 of FW-01
   logging event link-status
   switchport mode trunk
   channel-group 1999 mode active
!
interface Ethernet47
   description E47 (MLAG) of LIN-01-TRNS-SW-01
   logging event link-status
   speed forced 100gfull?????
   switchport mode trunk
   switchport trunk group MLAGPEER
   channel-group 2000 mode active
!
interface Ethernet48
   description E48 (MLAG) of LIN-01-TRNS-SW-02
   logging event link-status
   speed forced 100gfull?????
   switchport mode trunk
   switchport trunk group MLAGPEER
   channel-group 2000 mode active
!
interface Vlan2000
   description <== MLAG Peerlink ==>
   no autostate
   ip address 100.127.255.254/30
!
ip routing
!
mlag configuration
   domain-id MLAG-DOMAIN-2000
   local-interface Vlan2000
   peer-address 100.127.255.253
   peer-link Port-Channel2000
   reload-delay non-mlag 240
!
ip route 0.0.0.0/0 172.22.16.1??????