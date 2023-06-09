---
title: "eDiscovery (Premium) in Yammer"
f1.keywords:
- NOCSH
ms.author: pamgreen
author: ToniSFrench
manager: pamgreen
ms.date: 01/16/2020
audience: Admin
ms.topic: article
ms.service: yammer
ms.localizationpriority: medium
ms.custom: Adm_Yammer
search.appverid: 
- MET150
- YAE150
ms.assetid: a9a25f87-e643-41ce-9630-b74d10e40b1a
description: An overview about eDiscovery (Premium) in Yammer.
ROBOTS: NOINDEX, NOFOLLOW 
---

# eDiscovery (Premium) in Yammer networks

Yammer supports both eDiscovery and eDiscovery (Premium) within the Microsoft Purview compliance portal.

To use this functionality, your Yammer network will need to be in Native Mode. If your network was provisioned after January 9, 2020, you are already in Native Mode. If your network was provisioned *before* January 9, 2020, you will need to follow the steps in the [Native Mode Alignment Tool](../configure-your-yammer-network/overview-native-mode.md).

You can learn more about eDiscovery in the [Microsoft Purview compliance portal](/microsoft-365/) and [eDiscovery (Premium)](advanced-ediscovery.md) (coming soon for Yammer).

The processes outlined in the documentation explain how to run eDiscovery searches on all your Microsoft content. While Yammer isn’t discussed explicitly in those documents, the same processes that are mentioned apply to Yammer content. When writing a search query in either eDiscovery or eDiscovery (Premium), you can filter on Yammer content specifically by selecting **Yammer Messages** as the *Type* of content as shown in the screenshots below.

## eDiscovery

![screenshot showing eDiscovery in Yammer.](../media/kb/yam-ediscovery.png)

## eDiscovery (Premium)

![screenshot showing eDiscovery (Premium) in Yammer.](../media/yammer-advanced-ediscovery.png)

> [!NOTE]
> You do not need to select Yammer messages as the Type to ensure Yammer messages will be included in your results. This option allows you to filter so that your results only include Yammer messages.

When viewing Yammer content in the eDiscovery tools, you can expect the following information to be available:

- Message Body
- Author
- Recipients
- Timestamp

We plan to continue updating the service over time to include more information not listed above.

## See also

[Overview of eDiscovery in Yammer networks](overview-of-ediscovery.md)

[eDiscovery in Office 365](/office365/securitycompliance/ediscovery)

[Overview of the eDiscovery (Premium) solution in Microsoft Purview](/office365/securitycompliance/office-365-advanced-ediscovery)