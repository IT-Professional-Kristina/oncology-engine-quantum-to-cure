## Status: ✅ COMPLETE — 5/2/2026

# Phase 1 — Quantum Mechanics & Key Vault

## Azure Resources Created
- Resource Group: oncology-engine-rg
- Key Vault: oncology-keyvault-ka
- Secret: cyclophosphamide-dose-protocol (Enabled)

## What I Learned
- RBAC error taught me that Azure requires explicit 
  role assignments before accessing Key Vault secrets
- Assigned myself Key Vault Secrets Officer role
- Key Vault logs every access — full audit trail

## Clinical Connection
Chemo drug protocols stored as protected secrets.
Only authorized pharmacy staff can access formulations.
Mirrors HIPAA compliance requirements in real hospitals.

## AZ-900 Concepts Practiced
- Azure Key Vault
- RBAC role assignments
- Security & compliance
- PaaS managed security services
