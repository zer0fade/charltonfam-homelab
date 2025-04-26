# Storage

## ZFS Pool
- 2x 4TB NVMe drives
- ZFS Mirror with compression enabled

## Backup Strategy
- Regular ZFS snapshots
- Replication planning to remote site (future)
- Offsite backup (rclone / Backblaze / Oracle Object Storage)

## Future Work
- Test ZFS Send/Receive for disaster recovery
- Expand backup automation
