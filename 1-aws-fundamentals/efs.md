# EFS - Elastic File System
- managed network file system.
- can be mounted on many EC2 instances (multi-AZ)
- Highly available ,scale automatically , expensize and pay per use
- Compatible with Linux AMI (POSIX system)
- Encryption at rest using KMS

## Perfomance Mode
- you can set different performance modes for EFS at the creation time of your file system.
- General purpose
  - default and it's for latency-sensitive use cases.
  - So think about web servers, CMS, 
- Max i/o
  - higher latency, higher throughput and it's highly parallel.
  - big data , media processing type of need for your file system.

## ThroughputMode
- Burst
- Provisioned

## Storage Classes
- Uses a life cycle management feature
- Standard, Frequently accessed files.
- EFS-IA, Infrequently accessed

## Availability and Durability
- Regional
- EFS One zone -IA
