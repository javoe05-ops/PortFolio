# PortFolio
These are my solo projects that i have done myself to show my experience
# Windows Security Monitoring & Threat Detection Using Splunk

## Project Overview

This project focuses on building a Security Information and Event Management (SIEM) home lab using Splunk Enterprise to monitor, analyze, and investigate Windows security events.

The purpose of this project was to gain hands-on experience with cybersecurity monitoring and develop practical skills relevant to an entry-level Security Operations Center (SOC) Analyst role.

I configured Splunk to collect Windows Security Event Logs and created a custom security monitoring dashboard to track successful logins, failed login attempts, authentication activity, and suspicious source IP addresses.

The dashboard provides a centralized view of Windows security activity, allowing an analyst to identify unusual authentication patterns and investigate potentially suspicious events.

## Project Objectives

- Configure Splunk Enterprise for Windows Security Event Log monitoring.
- Collect and analyze Windows authentication events.
- Identify successful and failed login attempts.
- Monitor source IP addresses associated with failed authentication.
- Analyze security events using Splunk Search Processing Language (SPL).
- Create visual dashboards to monitor authentication activity.
- Practice investigating security events and documenting findings.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Splunk Enterprise | SIEM and security monitoring |
| Windows 10/11 | Operating system and log source |
| Windows Event Viewer | Security event investigation |
| SPL | Security log searches and analysis |
| GitHub | Project documentation and portfolio |

## Security Events Monitored

| Event ID | Description |
|---|---|
| 4624 | Successful logon |
| 4625 | Failed logon |
| 4672 | Special privileges assigned |
| 4798 | User's local group membership enumerated |

## Dashboard Features

The Splunk dashboard includes:

1. **Successful Logins:** Tracks successful Windows authentication events.
2. **Failed Login Attempts:** Monitors unsuccessful authentication attempts.
3. **Total Logons:** Displays the total recorded logon count.
4. **Failed Authentication by Account:** Identifies accounts associated with failed login attempts.
5. **Top 10 Source IPs:** Identifies IP addresses generating failed authentication events.
6. **Authentication Trends:** Visualizes successful and failed authentication activity over time.
7. **Recent Security Events:** Displays recent Windows security events, including timestamps, event IDs, usernames, and source IP addresses.

## Investigation Results

During the project, the Splunk dashboard displayed:

- 2,687 successful login events.
- 4 failed login attempts.
- 127.0.0.1 as the source IP displayed in the failed-login chart.

The investigation demonstrated how Windows authentication events can be monitored and visualized using Splunk.

The failed login activity was reviewed as part of the investigation. No confirmed security compromise was established.

## Skills Demonstrated

Through this project, I gained practical experience with:

- SIEM configuration and monitoring.
- Windows Security Event Log analysis.
- Splunk Search Processing Language (SPL).
- Authentication monitoring.
- Failed login investigation.
- Source IP analysis.
- Security dashboard development.
- Basic incident investigation and reporting.

## Project Outcome

Successfully developed a Windows security monitoring environment using Splunk Enterprise.

This project provided hands-on experience with security event collection, log analysis, authentication monitoring, and incident documentation.

It represents an introduction to the responsibilities and technical skills required for an entry-level SOC Analyst or Junior Cybersecurity Analyst position.

---

**Project Category:** Cybersecurity / SIEM / Threat Detection

**Difficulty:** Beginner

**Platform:** Windows

**SIEM:** Splunk Enterprise
