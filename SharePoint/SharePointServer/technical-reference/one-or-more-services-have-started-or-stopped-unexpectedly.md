---
title: "One or more services have started or stopped unexpectedly (SharePoint Server)"
ms.author: stevhord
author: bentoncity
manager: pamgreen
ms.date: 8/31/2017
ms.audience: ITPro
ms.topic: troubleshooting
ms.prod: sharepoint-server-itpro
localization_priority: Normal
ms.collection:
- IT_Sharepoint_Server
- IT_Sharepoint_Server_Top
ms.assetid: f91de311-e531-4a15-bcc4-b4af01774e0b
description: "Summary: Learn how to resolve the SharePoint Health Analyzer ruleOne or more services have started or stopped unexpectedlyfor SharePoint Server 2016 and SharePoint 2013."
---

# One or more services have started or stopped unexpectedly (SharePoint Server)

 **Summary:** Learn how to resolve the SharePoint Health Analyzer rule "One or more services have started or stopped unexpectedly" for SharePoint Server 2016 and SharePoint 2013. 
  
 **Rule Name:** One or more services have started or stopped unexpectedly. 
  
 **Summary:** A critical service required for the SharePoint farm to function is not running. 
  
 **Cause:** One or more critical services are not running on the specified server. 
  
 **Resolution: Start the service that is not running**
  
1. Verify that the user account that is performing this procedure is a member of the Administrators group on the local computer.
    
2. In Server Manager, click **Tools**, and then click **Services**.
    
3. Right-click the service that you want to start, and then click **Start**.
    

