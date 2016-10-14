---
title: "Appliance Monitoring (Analytics Platform System)"
ms.custom: na
ms.date: 07/27/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 253864fb-9178-41d2-a0ae-5dd9fd0a4fda
caps.latest.revision: 25
author: BarbKess
---
# Appliance Monitoring (Analytics Platform System)
This Appliance Monitoring Guide describes the tools and tasks for monitoring the SQL Server PDW appliance.  
  
## Contents  
  
-   [Basics](#Basics)  
  
-   [Related Monitoring Tasks](#Tasks)  
  
## <a name="Basics"></a>Monitoring Basics and Tools  
The values and information that can be monitored on the SQL Server PDW appliance are extensive. For example, the following are typical monitoring tasks.  
  
-   Check for any alert issued by SQL Server PDW.  
  
-   Monitor for failed hardware.  
  
-   Monitor for network connectivity problems.  
  
-   Check for errors returned to users during query processing.  
  
-   View the number of currently active sessions and queries.  
  
-   Check the status of loads, backups, and restores.  
  
### Appliance Monitoring Tools  
There are multiple tools available to monitor the appliance.  
  
Admin Console  
SQL Server PDW has an Admin Console. This is a web-based tool that displays information about queries, loads, backup and restore, locks, sessions, alerts, and appliance state. The Admin Console runs on the appliance; users connect to the Admin Console through Internet Explorer. For more information, see:  
  
-   [Monitor the Appliance by Using the Admin Console &#40;Analytics Platform System&#41;](../management/monitor-the-appliance-by-using-the-admin-console-analytics-platform-system.md)  
  
![PDW Admin Console Alerts](../management/media/SQL_Server_PDW_AdminConsol_Queries.png "SQL_Server_PDW_AdminConsol_Queries")  
  
System Views  
SQL Server PDW includes comprehensive system views that enable you to obtain detailed information about the appliance health, state, and performance. For a list of system views for monitoring tasks, see:  
  
-   [Monitor the Appliance by Using System Views &#40;Analytics Platform System&#41;](../management/monitor-the-appliance-by-using-system-views-analytics-platform-system.md)  
  
System Center Operations Manager (SCOM)  
SQL Server PDW has extensive integration with Systems Center Operations Manager. The management packs for SQL Server PDW are available as a free download. For more information about using System Center to monitor SQL Server PDW, see the following:  
  
-   [Monitor the Appliance by Using System Center Operations Manager &#40;Analytics Platform System&#41;](../management/monitor-the-appliance-by-using-system-center-operations-manager-analytics-platform-system.md)  
  
Custom Solutions  
For situations when System Center is not available with your data center monitoring tools, you can monitor the appliance by using a third-party monitoring solution. Most monitoring solutions support Transact\-SQL integration, so the system administrator can implement direct Transact\-SQL queries against your PDW appliance.  
  
If your monitoring solution does not support direct Transact\-SQL queries, or you do not have a monitoring tool, then you can use scripts to perform monitoring tasks, such as sending email when an alert occurs.  The TechNet wiki contains a scripted monitoring solution example.  
  
-   [Power Shell Monitoring Example for SQL Server PDW](http://go.microsoft.com/fwlink/?LinkId=248020)  
  
If you can’t access this article, see [NIB Join Our Communities  (Analytics Platform System)](../Topic/NIB%20Join%20Our%20Communities%20%20(Analytics%20Platform%20System).md).  
  
## <a name="Tasks"></a>Related Monitoring Tasks  
  
|Monitoring Task|Description|  
|-------------------|---------------|  
|Monitor the appliance by using the Admin Console.|[Monitor the Appliance by Using the Admin Console &#40;Analytics Platform System&#41;](../management/monitor-the-appliance-by-using-the-admin-console-analytics-platform-system.md)|  
|Monitor the appliance by using System Views.|[Monitor the Appliance by Using System Views &#40;Analytics Platform System&#41;](../management/monitor-the-appliance-by-using-system-views-analytics-platform-system.md)|  
|Monitor the appliance by using System Center|[Monitor the Appliance by Using System Center Operations Manager &#40;Analytics Platform System&#41;](../management/monitor-the-appliance-by-using-system-center-operations-manager-analytics-platform-system.md)|  
|Monitor the state of the appliance.|[Monitor Appliance Health State &#40;Analytics Platform System&#41;](../management/monitor-appliance-health-state-analytics-platform-system.md)|  
|Heartbeat Monitoring.|[Send Telemetry Feedback to Microsoft &#40;SQL Server PDW&#41;](../management/send-telemetry-feedback-to-microsoft-sql-server-pdw.md)|  
|Track appliance alerts.|[Track Appliance Alerts &#40;Analytics Platform System&#41;](../management/track-appliance-alerts-analytics-platform-system.md)|  
|Determine how much capacity is being used.|[View Capacity Utilization &#40;Analytics Platform System&#41;](../management/view-capacity-utilization-analytics-platform-system.md)|  
|Determine how often to poll the appliance.|[Determine Polling Frequency &#40;Analytics Platform System&#41;](../management/determine-polling-frequency-analytics-platform-system.md)|  
|When a cluster failure occurs, determine which cluster node failed.|[Determine Which Cluster Node Failed &#40;Analytics Platform System&#41;](../management/determine-which-cluster-node-failed-analytics-platform-system.md)|  
|Monitor loads.|[Monitor Loads &#40;SQL Server PDW&#41;](../sqlpdw/monitor-loads-sql-server-pdw.md)|  
|Monitor backups and restores.|[Monitor Backups and Restores &#40;SQL Server PDW&#41;](../sqlpdw/monitor-backups-and-restores-sql-server-pdw.md)|  
|Monitor the active queries.|[Monitoring Active Queries &#40;SQL Server PDW&#41;](../sqlpdw/monitoring-active-queries-sql-server-pdw.md)|  
  
## See Also  
[Common Metadata Query Examples &#40;SQL Server PDW&#41;](../sqlpdw/common-metadata-query-examples-sql-server-pdw.md)  
[Appliance Management Tasks &#40;Analytics Platform System&#41;](../management/appliance-management-tasks-analytics-platform-system.md)  
  