AH <> NB


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

Stop point to points cancel them

IP allocation should be networking bc networking will have to fix;... too many cidrs can't summarize, etc
