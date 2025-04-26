# Charlton Family Home Lab Documentation

Welcome to the Charlton Family hybrid home lab documentation repository.  
This site documents the technical architecture, infrastructure design, monitoring systems, and automation practices supporting the Charlton Family on-premises and cloud-integrated environment.

## Structure
- **Networking**: VLANs, network bonding, firewall segmentation
- **Compute**: Proxmox clusters, VMs, and LXC containers
- **Storage**: ZFS storage pools, backup and replication
- **Security**: PKI, certificate lifecycle management, VPN design
- **Monitoring**: Metrics ingestion, drift detection, security monitoring
- **Automation**: Terraform modules, Ansible playbooks, GitOps pipelines
- **Roadmap**: Milestones, completed work, future goals

## Local Development
To view and edit this documentation locally:

```bash
# Install MkDocs and Material theme
pip install mkdocs-material

# Serve the documentation locally
mkdocs serve
