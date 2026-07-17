# Log Analytics Workspace Deployment

## Project Objective

The goal of this step was to deploy an Azure Log Analytics Workspace that will serve as the central location for collecting, storing, and querying security logs for Microsoft Sentinel.

---

## Why a Log Analytics Workspace?

Microsoft Sentinel stores and analyzes security data inside a Log Analytics Workspace.

Without a workspace, Sentinel cannot ingest logs or perform threat detection.

---

## Configuration

| Setting | Value |
|----------|-------|
| Resource Group | Frank-SOC-Lab-RG |
| Workspace Name | SOC-LAW-01 |
| Region | Germany West Central |
| Subscription | Azure subscription 1 |

---

## Deployment

The Log Analytics Workspace was successfully deployed and is ready to receive logs from Azure resources.

---

## Screenshot

*Add a screenshot of the deployment or workspace overview here.*

---

## Skills Demonstrated

- Azure Resource Management
- Cloud Infrastructure Deployment
- Log Analytics Workspace Configuration
- Microsoft Sentinel Prerequisites

---

## Lessons Learned

A Log Analytics Workspace is the foundation of Microsoft Sentinel. It acts as the repository where logs are stored and queried using Kusto Query Language (KQL).
