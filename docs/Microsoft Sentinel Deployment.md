# Microsoft Sentinel Deployment

## Project Objective

The objective of this phase was to deploy Microsoft Sentinel on the Azure Log Analytics Workspace to provide Security Information and Event Management (SIEM) capabilities for the SOC lab.

Microsoft Sentinel enables centralized security monitoring, threat detection, investigation, and incident response by analyzing logs collected from connected resources.

---

## Why Microsoft Sentinel?

Microsoft Sentinel is Microsoft's cloud-native SIEM and SOAR platform.

By connecting Sentinel to the Log Analytics Workspace, the SOC gains the ability to:

- Collect security telemetry
- Perform threat hunting using Kusto Query Language (KQL)
- Create analytics rules
- Generate security alerts
- Investigate incidents
- Automate response through playbooks
- Visualize security data using workbooks

---

## Configuration

| Setting | Value |
|----------|-------|
| Resource Group | Frank-SOC-Lab-RG |
| Workspace | SOC-LAW-WE-01 |
| SIEM Platform | Microsoft Sentinel |
| Deployment Method | Azure Portal |

---

## Deployment

Microsoft Sentinel was successfully enabled on the Log Analytics Workspace.

Once deployed, the workspace became Sentinel-enabled, allowing it to ingest security logs and support threat detection, incident management, hunting queries, analytics rules, automation, and dashboards.

---

## Screenshot

![Microsoft Sentinel Overview](../images/03-microsoft-sentinel-overview.png)

---

## Skills Demonstrated

- Microsoft Sentinel Deployment
- SIEM Configuration
- Azure Security Services
- Cloud Security Monitoring
- Security Operations Center (SOC) Fundamentals

---

## Lessons Learned

Microsoft Sentinel extends Azure Monitor and Log Analytics into a full cloud-native SIEM and SOAR solution. While Log Analytics stores the data, Sentinel provides the intelligence needed to detect threats, investigate incidents, and automate security operations.

---

## Why this Matters in a SOC

Microsoft Sentinel serves as the central platform for monitoring and responding to security events. SOC analysts rely on Sentinel to correlate events, investigate suspicious activity, create detection rules, perform threat hunting, and manage incidents from a single interface.
