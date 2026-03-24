# Intune lastSyncDateTime Monitoring (Graph Automation + Alerting)

## Problem
Device health issues often show up first as stale Intune sync times, but many environments lack proactive detection.

## Solution
Created a monitoring workflow that:
- Pulls device sync telemetry via Microsoft Graph (e.g., lastSyncDateTime)
- Flags anomalies based on thresholds (per platform/team)
- Alerts operations channels with actionable device lists
- Can be scheduled and operationalized as part of a broader device health program

## Tech stack
PowerShell, Microsoft Graph API, automation scheduler (Azure Automation / Functions / CI runners), alert routing (email/Slack/Teams).

## Outcomes (estimates — adjust with your numbers)
- Reduced time-to-detect stale devices from **days → same-day**
- Improved remediation throughput by producing prioritized device lists
