AH <> NB



ciphertrust login: ksadmin
You are required to change your password immediately (root enforced)
Enter new UNIX password: 


nmcli con mod eth0 ipv4.method manual ipv4.address 192.168.49.10/24 ipv4.gateway 192.168.49.1 ipv4.dns 172.22.20.5,192.168.65.5


new monitoring server
For 08282023
Replace all 192.168.
Netbox
Disable wifi-based URL filtering, move to FW
change mgmt types, BAU, emergency, scheduled, 



>>>>>Since we last spoke<<<<<
Local and jumpbox computer application issues are resolved
I worked on internal perimeter audit (wifi and firewall)
Troubleshoot a Cathy Huges Google Drive issue and a David Klun SQL performance issue
Surveyed Linwood's IDFs and MDF
Physically mapped out the Linwood firewall uplinks in preparation for the firewall cutover
Attended Infrastructure team's weekly meeting
Attended new hire orientation
Completed mandatory new hire security training
I have r/o access to the TierPoint switches
Meeting with Shlomo to discuss Israel office wifi. Advised Shlomo on best practices and suggested he create an RFP along with other suggestions. Per Shlomo, he will keep me in the loop. Additionally, we also discussed onprem to AWS latency.

I now have r/o AWS access to some to the "shared" VPCs.

Reviewed TierPoint's switches with emphasis on AWS performance


>>>>>Questions from me to him<<<<<

Which platform to use a network engineering project board? Use Monday or JIRA? I prefer Monday for projects but I'll use what works best for the team.
    - Where in Confluence
    - Where in Monday
    - WHere in Jira  <<<<<<<<<<>>>>>>>>>> noam says this one.. 


>>>>>Moving Projects/tasks forward<<<<<
Need access to Linwood non-prod fw.
    - Apply some best practiecs w/o jeprodizing cutover dates

Thales - not first meeting but ... where do we have them. Take a look at prior implemtation... appliance or virtual. appliance onsite? 


2 bgp lines.. 1gig/1gig 50-60 max simutaneiouly guest wifi <<<   >>>

>>>>>Strategy/My Direction/Recommendation Actions/Recommendation Products<<<<<
Cancel TierPoint.. all inhouse. 
NetworkEngineering@crossriver.com // NetOps@crossriver.com   
replace everything except for firewalls, Ubiquity, HPE, 


>>>>>Concerns/Blockers/Questions<<<<<

Maintenance days applies to datacenters and AWS or offices as well? sept 15th to oct 8th is change freeze
As tickets come in, questions on if the person, APP, port, etc should be permitted
stop attending non-network meetings... 
Title change - Senior Network engineer
Firewalls not in Solarwinds, they should be

Network has own budget, create own budget

Current network efforts/access - Peel back
    - A lot of ppl with r/o access
    - Making changes even from mobile devices, who, and alerts for every change
    - focus on their domain
    - separation of duties
    - Shlomo, Mark, helpdesk, Sunny, Yuri (linwood)


>>>>>Working on Next<<<<<

Understand WAN
    - Streteched VLANs btwn sites?
    - P2Ps
    - Loops
    - Scalability
    - Dynamic routing ready
    - IP Layout
    - VLAN Allocation
    - AWS VPC networking

netbox is DCIM

VFO to AWS performance based on current access


I do IP allocation



09112023



Lab setup
- FW is WIP
- AWS waiting for approval
- EOW ready



ore-al

Linwood ready

Israel office

Not Infrastructure

Peel away from others

Meet CISO - will send audit reports.. said all firewalls are in scope

Meet Urile - said we need to block AI and apply web filtering







To Be Discussed on 09182023


Reached out to Windstream to confirm


Fixed Cathy issue with Google and Twitter
Moved tickets to my queue

Remove from infra email distro
Add to other receive groups


Saw the push for snmp, now I'll stage another push
Then add to monitoring. Once in Sw integrate with pager duty


Network staging is 30% complete 
- missing isp
- test computers
ip address



Todo
Clean out old queue
Start preparing Linwood 

Stop point to points cancel them

IP allocation should be networking bc networking will have to fix;... too many cidrs can't summarize, etc

idan
asked windstream
the revert works in lab

pagerduty
email when changes made

let me make your lives easier

JAIME DAVILA asked if FW team is in US or Israel... doesn't matter should be the message, it will get done and escalate wisely if urgent... 24/7.. also, FW team change to network team or network engineering

445 access fw open





>>>>>> 09-25-2023<<<<<<


Linwood needs time to review. FW is not standard and someone trying new methods

diagrams

late night changes.. a series of changes <<<<<<<>>>>>>> prepare Operations for the move.. have list from JOhn Butkowski

creds for pafw service account

second ISP

AWS failvoer
need second IPSEC tunnel

Firewall monitroing is in Solarwinds.. except for brooklyn. 

DX outage... timeframe with Randy

open fw tickets down to 150 from 200

Need access to perfrom failover.. not infra doing failover

stop attending non-network meetings... 
Title change - Senior Network engineer

tell teams to standdown

Weeklys with brian

How long wait for commits? 

failover in controled env... 

israel 


10/09/2023


splunk access


WE NEED a deprovision process to clear-up firewall rules when a user leaves or computer/IP is decom'd.


IT-Tatical


can't do debugs, captures, or clears..


;;;


Uriel and thales
Isrel BoM
prep to migrate linwood firewall but need access - 
    - access to tshoot fiserv, fednow, fastly to do debugs and captutres
AWS automatic failover







10/23/2023

remind ppl to add brief reason to firewall request.

Will advise of notable changes that are not BAU

remove me from IT Engineering Zendesk group

curse to have users w/ access bc they tell what to do, not what they need.. infra should not do that
remove their access, they are viewing sensivte data

now have moniotring from VFO to AWS. 

tshoot trustly and fednow

deprovision old resources ie users, computers, servers

resolve fiserv issue with captures

remove access from others

fix issue with groups query

email to remove computer from domain so computer can ping AWS


10/30/2023

Fednow connectivity issue

https://crossriver.zendesk.com/agent/tickets/561503

too many AD groups... causing issues.. manually add

change title. goal of network architect... just irewall... wifi updgrades.

will begin tagging you on anything new I add to JIRA

unable to get to DC due to intermittent connectivity

if it is not urgent no one should be coming to you. 

who assigns IP blocks

Kadija ticket 


number of Pano users is 12 but number of users w/ local fw access is 19. 

vault 


office migration probably this week.. ISP changes, fiber and riser chanages, etc


BGP to AWS
Move Parker infra



BGP btwn offices
AWS egress 



11/20/2023



FedNow

cathy investigating last outage

Yuri with some IT audit tickets

Ill-Ye-yah

Il-yah and Azure GP SSO/MFA - - -domain and cert to test with

which tickets to work... new installs, cleartouch, rdp, but put others in saved stage for you to push?

test linwood failover

firewalls out of sync

ppl doing network functions.. moving equipment.

Ofek Edri





11/27/2023

Tickets.. which okay to push other than new hires? ppl still using zendesk

deeper discussion on DC to AWS and AWS internet ingress/egress 

Ilya 

network monitoring is weak

cleanup old network tickets from the Infra team

cancel the 10Gig P2P .. cancel Fios  

test linwood failover 

Assiting Uril with Fortigate access 

Fednow not a network issue

Fiserv on hold

Slow down so cleanup sprint and on track

Linwood 5th floor? 6 months more at least?

IP whitelisting stays permanent or rememoved after some time?


gig-sa is aws rep
wiz? sec tool
sre send the ticket #?





????? 12042023

Thales

review tickets

monitor

Access to IT Tactical

FW renewal

AWS

jigNah

AWS



BYOL
Transit gateway - sit in inspection VPC
firmware upgrade requirements
active sessions and new sessions
illgeal IP usage for the firewall? cgn
if transit gwty is required are there bandwith limitations for a custome w/ 10G or 100G? ipsec encrption
ELB difference or changes?
BYO /24?
number of advertised bgp prefixes
traffic decryption?
remove securty and NACLs is common?

firewalls active active or active standby

AWS outage dual AZ or other regaion?

10,000 prefixes 


gatway loadbalancer

vest after how oong? 160 stock
1 yr then 25%
100k for examplenfrpom


12/11/2023
replace SW
cert
no network changes w/o NOC or Ali




