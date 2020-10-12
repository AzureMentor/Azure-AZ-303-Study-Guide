# AZ-303: Implement and Monitor an Azure Infrastructure (50-55%)

## Implement cloud infrastructure monitoring
- monitor security
    - [Azure infrastructure monitoring](https://docs.microsoft.com/en-us/azure/security/fundamentals/infrastructure-monitoring)
    - [Security Control: Logging and Monitoring](https://docs.microsoft.com/en-us/azure/security/benchmarks/security-control-logging-monitoring)
    - [Strengthen your security posture with Azure Security Center](https://docs.microsoft.com/en-us/azure/security-center/security-center-monitoring)
- monitor performance
  - configure diagnostic settings on resources
    - [Create diagnostic settings to send platform logs and metrics to different destinations](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/diagnostic-settings)
    - [Resource Manager template samples for diagnostic settings in Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/samples/resource-manager-diagnostic-settings)
  - create a performance baseline for resources
    - [Metric Baseline - Get](https://docs.microsoft.com/en-us/rest/api/monitor/metricbaseline/get)
  - monitor for unused resources
    - [Quickstart: Monitor an Azure resource with Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/learn/quick-monitor-azure-resource)
  - monitor performance capacity
    - [Collect event and performance data](https://docs.microsoft.com/en-us/azure/azure-monitor/learn/quick-collect-azurevm#collect-event-and-performance-data)
  - [visualize diagnostics data using Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/visualizations)
    - [Visualizations](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/workbooks-overview#visualizations)
    - [Azure Monitor Workbooks](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/workbooks-overview)
- monitor health and availability
  - [monitor networking](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/network-insights-overview)
  - [monitor service health](https://docs.microsoft.com/en-us/azure/service-health/)
  - [Resource Health](https://docs.microsoft.com/en-us/azure/service-health/resource-health-overview)
- monitor cost
  - monitor spend
    - [Use cost alerts to monitor usage and spending](https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-alerts-monitor-usage-spending)
    - [Checklist - Monitor cost](https://docs.microsoft.com/en-us/azure/architecture/framework/cost/monitor-checklist)
  - report on spend
    - [Download or view your Azure billing invoice and daily usage data](https://docs.microsoft.com/en-us/azure/cost-management-billing/manage/download-azure-invoice-daily-usage-date)
- configure advanced logging
  - implement and configure Azure Monitor insights, including:
    - [App Insights](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/insights-overview#application-insights)
    - [Networks](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/insights-overview#azure-monitor-for-networks-preview)
    - [Containers](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/insights-overview#azure-monitor-for-containers)
  - [configure a Log Analytics workspace](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-platform-logs)
- configure logging for workloads
  - [initiate automated responses by using Action Groups](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/action-groups)
- configure and manage advanced alerts
  - collect alerts and metrics across multiple subscriptions
    - [Manage alert instances with unified alerts](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-managing-alert-instances)
    - [Create diagnostic settings to send platform logs and metrics to different destinations](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/diagnostic-settings)
    - [Overview of alerts in Microsoft Azure](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-overview)
    - [Create a Log Analytics workspace in the Azure portal](https://docs.microsoft.com/en-us/azure/azure-monitor/learn/quick-create-workspace)
  - [view Alerts in Azure Monitor logs](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-log)

## Implement storage accounts
- select storage account options based on a use case
- configure Azure Files and blob storage
- configure network access to the storage account
- implement Shared Access Signatures and access policies
- implement Azure AD authentication for storage
- manage access keys
- implement Azure storage replication
- implement Azure storage account failover

## Implement VMs for Windows and Linux
- configure High Availability
- configure storage for VMs
- select virtual machine size
- implement Azure Dedicated Hosts
- deploy and configure scale sets
- configure Azure Disk Encryption

## Automate deployment and configuration of resources
- save a deployment as an Azure Resource Manager (ARM) template
- modify ARM template
- evaluate location of new resources
- configure a virtual disk template
- deploy from a template
- manage a template library
- create and execute an automation runbook

## Implement virtual networking
- implement VNet to VNet connections
- implement VNet peering

## Implement Azure Active Directory
- add custom domains
- configure Azure AD Identity Protection
- implement self-service password reset
- implement Conditional Access including MFA
- configure user accounts for MFA
- configure fraud alerts
- configure bypass options
- configure Trusted IPs
- configure verification methods
- implement and manage guest accounts
- manage multiple directories

## Implement and manage hybrid identities
- install and configure Azure AD Connect
- identity synchronization options
- configure and manage password sync and password writeback
- configure single sign-on
- use Azure AD Connect Health

[Return to Table of Contents](README.md)