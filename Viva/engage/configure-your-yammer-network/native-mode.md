---
title: "Prepare a Yammer network for Native Mode for Microsoft 365"
f1.keywords:
- NOCSH
ms.author: pamgreen
author: v-jebizie
manager: pamgreen
ms.date: 01/21/2020
audience: Admin
ms.topic: article
ms.service: yammer
ms.localizationpriority: medium
ms.custom: Adm_Yammer
search.appverid: 
- MOE150
- MET150
description: "Prepare your Yammer network for Native Mode for Microsoft 365."
---

# Configure your Yammer network for Native Mode for Microsoft 365

## Requirements for Native Mode

Native Mode has the following requirements:

- There can only be [one Yammer network on the tenant](consolidate-multiple-yammer-networks.md).

- All domains on the tenant are associated with the Yammer network, and there are no domains on the Yammer network that aren't on the tenant.

- All Yammer files must be [stored in SharePoint](https://go.microsoft.com/fwlink/?linkid=2111253).

- Retention mode in Yammer is set to Archive.

- All users must be in Azure Active Directory ("AAD"). AAD enforces Office 365 identity and, any users who aren't mapped to the network, must be deleted.

- There can't be any unlisted private groups.

- All existing groups must be Microsoft 365 connected.

- There can't be any external groups. Support for external groups is planned but isn't available with the initial release of Native Mode.

- There can't be any network-level or thread-level guests.

 > [!NOTE]
> Native Mode is strongly recommended for reasons of security, compliance, and Microsoft 365 integration.

## How does the Tool work with your network?

The Tool prepares your network for Native Mode by disabling some features and mitigating previously created instances of those features. Those changes include:

- Any unlisted private groups in your network will be changed to private listed groups. Users will no longer be able to create unlisted private groups.

- External groups in Yammer will no longer be supported, all external groups will be made internal only, and any external users in those groups will no longer have access to the group or its contents. Support for Azure B2B-based external groups is expected at a later date.

- Adds the Global admin to unconnected groups that either have no owners at all or that have no owner with Microsoft 365 Group creation rights. It doesn't add them to unconnected groups if the owner does have Microsoft 365 Group creation rights.

- Connects all unconnected Yammer groups after applying the changes mentioned in the previous three bulleted items above.

- Prevents files from being uploaded in Yammer Private messages, and deletes all files previously uploaded in Yammer Private messages.

- Deletes all internal users (and their associated files and Private messages) in the network who aren't mapped to an Office 365 identity in AAD.

- Disables support for guests in the network, and removes existing guests from the network, along with their associated Private messages and files.

- Disables support for adding guests to an individual thread. Guests who were previously added to individual threads will no longer have access.

- Deletes all group messages and files for previously deleted groups. Going forward, group messages will be deleted consistent with your network's retention policy.

- Locks your network into Native Mode.

- Begins ingesting your data into the Security & Compliance Center to support eDiscovery.

>[!CAUTION]
> Once you have started alignment through the Tool, the change is **irreversible**.
> Notify users *before* you run the Alignment Tool about the above changes so that they are prepared and not surprised.

## While the tool is running

- Group updates won't work on unconnected groups.

## Related articles

[Overview of Native Mode](overview-native-mode.md)

[Yammer files in Native Mode for Microsoft 365](files-in-native-mode.md)

[Troubleshoot problems with Native Mode for Microsoft 365](../troubleshoot-problems/troubleshoot-native-mode.md)
