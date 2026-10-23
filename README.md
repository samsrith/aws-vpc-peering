# aws-vpc-peering
AWS VPC Peering project with private EC2 connectivity and bastion host

# AWS VPC Peering Project

## Project Overview
This project demonstrates connectivity between two AWS VPCs using VPC Peering, private EC2 instances, route tables, security groups, and a bastion host.

## AWS Configuration
- **Region:** US East (N. Virginia) — `us-east-1`
- **VPC A CIDR:** `10.10.0.0/16`
- **VPC B CIDR:** `10.20.0.0/16`
- **Bastion private IP:** `10.10.1.10`
- **App-A private IP:** `10.10.2.10`
- **App-B private IP:** `10.20.1.10`

## Validation
- App-A to App-B private connectivity: successful
- App-B to App-A private connectivity: successful
- SSH access to private instances through the bastion: successful

## Evidence
Screenshots and the final project report will be added to this repository.

## Security
Private keys, passwords, and AWS credentials are not included in this repository

## Cleanup and Evidence Notes

AWS lab resources were deleted after the connectivity tests.

The recorded validation included:
- App-A to App-B private-IP ping: successful
- App-B to App-A private-IP ping: successful
- SSH access to App-B through the bastion: successful

The controlled ICMP failure-and-recovery test was not captured in the available evidence.
