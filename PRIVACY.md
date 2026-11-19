# Privacy Policy — PureForge Studio

**Effective Date:** November 19, 2026  
**Vendor:** PureForge Studio

## 1. Zero-Egress Architecture ("Runs on Atlassian")
All Atlassian Cloud applications published by **PureForge Studio**—including **Pure-Forge SVG Mermaid Studio**, **Pure-Forge Markdown Tree Studio**, and **Pure-Forge Bulk Label Governance**—are built exclusively on the native **Atlassian Forge** platform with **zero external network egress** (`permissions.external` is completely omitted).

## 2. Personal Data & PII Declaration
- **No Personal Data Collected or Stored:** Our applications **do not** collect, copy, cache, or store any Personal Data or Personally Identifiable Information (PII) such as user names, email addresses, IP addresses, or Atlassian `accountId` references.
- **No External Servers or Third-Party Processors:** All application compute executes inside Atlassian-managed Forge functions and the user's web browser. All configuration or diagram state is stored exclusively inside your own Atlassian Cloud tenant via the native Atlassian Forge Storage API (`storage:app`).
- **No Analytics or Tracking Cookies:** Our applications embed zero third-party scripts, zero external CDNs, and zero telemetry trackers.

## 3. Data Retention & Deletion
Because all application state resides solely within your Atlassian Cloud instance's Forge storage partition, uninstalling the application or deleting content within your Jira/Confluence site immediately removes the associated data in accordance with Atlassian Cloud's platform lifecycle.
