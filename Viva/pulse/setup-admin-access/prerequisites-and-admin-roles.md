---
title: Prerequisites and admin roles
description: "Prerequisites and admin roles"
ms.reviewer: 
ms.author: michellehu
author: michellehu-msft
manager: alisaliddle
audience: Admin
f1.keywords: NOCSH
ms.date: 06/02/2023
ms.topic: article
ms.service: viva
ms.localizationpriority: medium
ms.collection: m365initiative-viva-pulse  
search.appverid: MET150
---

# Prerequisites and admin roles

> [!NOTE]
> This article applies to a preview version of Microsoft Viva Pulse. You must be in the Public Preview program to access it. See [Set up Viva Pulse Public Preview](./set-up-viva-pulse-public-preview-for-your-organization.md) to enable the Viva Pulse Public Preview for your organization and enable Teams Activity feed notifications for users in your tenant. Also, please note that customer support will only be available in English for Public Preview. Features are subject to change.

## Prerequisites

You will need to have Microsoft Teams deployed for your organization to use Viva Pulse in Microsoft Teams. Viva Pulse will also be available as a web experience for which users will not need a Microsoft Teams application.

> [!IMPORTANT]
> Viva Pulse requires its users to be assigned Microsoft Forms licenses to send a Viva Pulse request. A user will not need a Microsoft Forms license to respond to a pulse request. If there are any tenant-wide conditional policies set up for Microsoft Forms that require users to accept terms of use, those policies will be bypassed for a seamless experience.

## Admin roles and permissions

The following roles and permissions are required to set up Viva Pulse.

| Roles | Permissions |
| ----------- | ----------- |
| Microsoft 365 Global Admin | The Microsoft 365 Global Admin has global access to most management features and data across Microsoft online services. For Viva Pulse, the Microsoft 365 Global Admin can install and pin the Viva Pulse app in Microsoft Teams, assign a user to the Viva Pulse Admin role, and manage in-app Viva Pulse settings as well. |
| Viva Pulse Admin | The Viva Pulse Admin needs to be assigned by the Microsoft 365 Global Admin. The Viva Pulse Admin can manage the in-app Viva Pulse settings. |
| [Microsoft Teams Admin](/microsoftteams/using-admin-roles) | The Microsoft Teams Admin can pin and install the Viva Pulse Admin in Teams for a customer tenant, as well as manage teams Teams app policies. |