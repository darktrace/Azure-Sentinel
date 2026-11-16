| **Version** | **Date Modified (DD-MM-YYYY)** | **Change History**                          |
|-------------|--------------------------------|---------------------------------------------|
| 3.2.0       | 12-11-2026                     | Added the **Darktrace SecureAI Data Connector** to push events to the Microsoft-managed PartnerRiskEvents shared table without custom table deployment. The DCR preserves the input contract and renames ResourceId, ResourceType, and ResourceName to TargetResourceId, TargetResourceType, and TargetResourceName; shared-table queries filter Darktrace events. |
| 3.1.1       | 30-06-2026                     | Fixed link to Darktrace set up guide        |
| 3.1.0       | 17-06-2026                     | Added modelBreaches and accountName to DarktraceIncidents_CL, accountName to DarktraceModelAlerts_CL. Updated analytic rules with Account entity mapping for SaaS/identity correlation. |
| 3.0.0       | 06-03-2026                     | Added new Darktrace ActiveAI Security Platform CCF data connector, DCR, custom tables, workbook, and two new analytic rules; relabeled legacy REST API connector, workbook, and analytic rules as (Legacy)                    |
