NAT + DHCP + Internet Simulation

It covers multiple CCNA exam topics:
-------------------------------------------------
DHCP Server

NAT Overload (PAT)

Inside/outside interfaces

Default routes

End-to-end “Internet” simulation

LAN-to-WAN communication

TOPOLOGY
-------------------------------------------------
PCs (LAN) → Switch → R1 → ISP Router → Internet Server

Devices:
-------------------------------------------------
1 switch

1 LAN router (R1)

1 ISP router (R2)

2 PCs

1 “Internet Server” (Cloud or a server)

IP Addressing Plan
-------------------------------------------------
LAN Side (inside)

Network: 192.168.10.0/24

DHCP pool: 192.168.10.100–192.168.10.200

Default gateway (R1): 192.168.10.1

WAN Link (R1 ↔ R2)

R1 (g0/1): 10.0.0.1/30

R2 (g0/1): 10.0.0.2/30

Internet Side

create a server: 172.16.1.10/24
