---
title: Open the Group Policy Management Console to IP Security Policies (Windows)
description: Learn how to open the Group Policy Management Console to IP Security Policies to configure GPOs for earlier versions of the Windows operating system.
ms.assetid: 235f73e4-37b7-40f4-a35e-3e7238bbef43
ms.reviewer: 
ms.author: dansimp
ms.prod: m365-security
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.localizationpriority: medium
author: dansimp
manager: dansimp
audience: ITPro
ms.collection: M365-security-compliance
ms.topic: conceptual
ms.date: 09/08/2021
ms.technology: mde
---

# Open the Group Policy Management Console to IP Security Policies

**Applies to**
-   Windows 10
-   Windows 11
-   Windows Server 2016 and above

Procedures in this guide that refer to GPOs for earlier versions of the Windows operating system instruct you to work with the IP Security Policy section in the Group Policy Management Console (GPMC).

**To open a GPO to the IP Security Policies section**

1. Open the Group Policy Management console.

2. In the navigation pane, expand **Forest:** *YourForestName*, expand **Domains**, expand *YourDomainName*, expand **Group Policy Objects**, right-click the GPO you want to modify, and then click **Edit**.

3. In the navigation pane of the Group Policy Management Editor, expand **Computer Configuration**, expand **Policies**, expand **Windows Settings**, expand **Security Settings**, and then click **IP Security Policies on Active Directory (**<em>YourDomainName</em>**)**.
