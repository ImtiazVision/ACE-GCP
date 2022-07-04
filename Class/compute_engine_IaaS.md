### Compute Engine as IaaS 

It is an infrastructure as a service. 

It has machine rightsizing, Global load balancing etc. features. 

### Storage 

SSD disk 

### VM access

Linux: SSH. port 22
Windows: RDP

### Availability policy: Automatic changes 

- Automatic restart 
- On host maintenance
- Live migration 

### Preemptible 

- VM might be terminated at any time
- It is cost effective 

### Sole-tenant node 

- To keep our instances physically separated (physically isolate workloads)
- It saves cost (80% discount & cost effective)

### Shielded VMs offer verifiable integrity

- Secure Boot
- Integrity monitoring
- Virtual trusted platform module

### Images 

- Public base images


- Custom images 


### Boot disk 

- Base image is loaded onto root disk during first boot

### Persistent disks

- Attached to a VM through the network interface
- HDD or SSD
- Dynamic disk resizing
- Zonal or Regional disk
- Performance: Scales with size
- All the data are encrypted by Google by default
- Durable storage
- Snapshots: incremental backups 
- Can be attached in read-only mode

### Snapshot use cases

- Back up data
- Migrate data between zones
- Transfer data to SSD to improve performance 