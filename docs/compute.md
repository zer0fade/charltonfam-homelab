# Compute and Virtualization

## Proxmox Environment
- Proxmox VE 8.4.1
- Primary host: HP EliteDesk G9
- Bonded network interfaces (2.5GbE)

## VM Inventory
| VM Name | Role | Location | Notes |
|:--------|:-----|:---------|:------|
| rmv-addc01 | Active Directory Domain Controller | Home | Primary |
| rmv-addc02 | Active Directory Domain Controller | Home | Redundant |
| irv-addc01 | Active Directory Domain Controller | Remote Site | Primary |
| irv-addc02 | Active Directory Domain Controller | Remote Site | Redundant |
| ConfigMgr | Configuration Manager | Home | SCCM and software updates |
| SQL Server | SQL backend | Home | Backend for ConfigMgr |
| Wazuh Manager | Security Monitoring | Home | Log aggregation |

## Future Work
- Expand to second Proxmox node for HA
- Template library refresh
