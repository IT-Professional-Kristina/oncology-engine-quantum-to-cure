## Status: ✅ COMPLETE — 5/2/2026

# Phase 4 — Gravity & Virtual Machine

## VM Configuration Designed
- Name: oncology-app-server
- Image: Ubuntu Pro 24.04 LTS x64 Gen2
- Size: Standard B1s (1 vCPU, 1GB RAM)
- Authentication: Password — oncologyadmin
- Virtual Network: oncology-vnet
- Subnet: oncology-subnet
- Inbound ports: None (secured)
- Resource Group: oncology-engine-rg

## Subscription Limitation Encountered
Free tier subscription quota does not support 
B1s VM deployment in East US region.
Error: NotAvailableForSubscription
Next step in production: Request quota increase
via Azure Support or upgrade subscription tier.

## What This Taught Me
- Azure free subscriptions have regional VM quotas
- VM sizing affects regional availability
- Quota requests are standard in enterprise Azure
- Full VM architecture was designed and documented
  even without deployment

## Clinical Connection
VM represents the central oncology application 
server — the gravitational core running Epic Beacon
inside the hospital network. Every clinical subnet
connects to this compute core.

## AZ-900 Concepts Practiced
- Virtual Machines (IaaS)
- VM sizing and pricing tiers (B1s)
- VNet and subnet integration
- Subscription quotas and limits
- Azure regions and availability zones
- Network security groups
