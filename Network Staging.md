Network Staging

Linwood CIDR: 10.215.0.0/16
PA-820

Hostname: DTC09-01-FW-01



AWS
AWS CIDR: 10.25.0.0/16

10.25.0.0/16
10.25.0.0/27
10.25.0.64/27

TGW-VPC-10_25_0_0__24


EndPoint10A-10_25_10_0
EndPoint10B-10_25_10_0


EndPoint20A-10_25_20_0
EndPoint20B-10_25_20_0

DTC09-VPN-DX-Pri = 131.239.170.93

prod>>>>>>.

Customer gateways  >> crb_customer_dx_gateway  >> 69.210.70.91 >> BGP ASN 65000
VPN connections >> AWS_VPN_CRB_DX >> static >> 69.210.70.91
Direct Connect > Virtual interfaces >> ASN 7224 >> AWS side 69.210.70.90/31


131.239.170.93(CrownCastle) is considered our DX so should be in VLAN 2014
(Spectrum) is considered our internet so should be on VLAN 1515


10.25.10.4
10.25.10.5
10.25.10.7
10.25.10.11