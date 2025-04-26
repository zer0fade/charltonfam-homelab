# Networking

## Overview
- Bonded NICs (802.3ad LACP)
- VLAN segmentation
- Firewall architecture via Ubiquiti UDM Pro Max
- Site-to-site VPN tunnels

## VLANs
| VLAN ID | Purpose | Subnet | Notes |
|:--------|:--------|:-------|:------|
| 200 | Server/VM Traffic | 10.10.200.0/22 | Main VM bridge (`vmbr0v200`) |

## Future Work
- Additional VLANs for IoT, Management, Guest Wi-Fi segmentation
- Enhanced firewall rule hardening
