# Enterprise Network Design

## Project Overview

Designed and configured a simulated enterprise network for a fictional healthcare technology company using Cisco Packet Tracer.
The objective was to establish communication between multiple departments while implementing basic network segmentation and access controls.

## Technologies Implemented

- VLANs and 802.1Q trunking
- Router-on-a-stick inter-VLAN routing
- IPv4 addressing and subnetting
- Extended access control lists (ACLs)
- Network connectivity testing and troubleshooting

## Network Architecture

The network consists of three departmental VLANs:

| Department | VLAN | Subnet |
|---|---|---|
| Administration | 10 | 192.168.10.0/24 |
| IT | 20 | 192.168.20.0/24 |
| Guest | 30 | 192.168.30.0/24 |

A Cisco router provides inter-VLAN routing, while an extended ACL restricts Guest traffic from accessing the Administration and IT networks.

## Verification

- Successfully tested inter-VLAN connectivity.
- Verified that Administration could communicate with IT.
- Confirmed that Guest-originated traffic to internal departmental networks was blocked.
- Resolved an initial trunk connectivity issue caused by a disabled router interface.

## Future Improvements

- DHCP configuration
- Additional switches and departments
- Multi-site routing with OSPF
- Network redundancy and failover testing
