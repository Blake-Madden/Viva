---
title: Enable browser optimized playback
ms.author: bhaswatic
author: bhaswatic
manager: pamgreen
ms.reviewer: chrisarnoldmsft
ms.date: 12/04/2023
audience: admin
ms.topic: article
ms.service: viva
ms.subservice: viva-learning
search.appverid: MET150
ms.collection:
  - enabler-strategic
  - m365initiative-viva-learning
  - Tier1
ms.localizationpriority: medium
description: Enable browser optimized playback to play SAP SuccessFactors courses in Viva Learning.
---

# Enable browser optimized playback

Viva Learning and SAP SuccessFactors integration allows seamless authentication (SSO) and browser-optimized playback. Users can access SAP SuccessFactors content inline within Viva Learning instead of launching content in a browser.  

Browser optimized is optimized for Teams desktop and web. It loads the SuccessFactors embedded player.

SAP SuccessFactors does not provide support for embedded content player in mobile applications. When using the Teams mobile app, browser-optimized loads the SAP SuccessFactors details page.

> [!IMPORTANT]
> The ability to play SAP SuccessFactors courses inline in Viva Learning is supported for SuccessFactors version 2205 (May 2022) and earlier. Changes introduced within the SuccessFactors 2211 (November 2022) release breaks the in-app play of content. We are currently working with SAP SuccessFactors to resolve this issue and will provide updates as soon as they are available.

Content classified as online and instructor-led with online are consumed within Viva Learning and other content classifications are launched in the browser.

![Screenshot that shows how inline content is consumed within Viva Learning.](../media/learning/inline-content-consumption.png)

## Pre-requisite for enabling browser optimized playback and SSO

Refer to the [Microsoft Entra single sign-on (SSO) integration with SAP SuccessFactors](/azure/active-directory/saas-apps/successfactors-tutorial) topic for configuration information on enabling browser-optimized playback and SSO.

Ensure that the SSO configuration on Microsoft Entra ID and SAP SuccessFactors is the same and that the users login method on SAP SuccessFactors is set to "SSO."

Log in to Teams and Windows with the same user account for optimized consumption of SAP SuccessFactors content within Viva Learning.

You may encounter a "refused to connect" error or a blank screen the first time you consume SAP SuccessFactors content optimized in the browser within Viva Learning. The content plays successfully on subsequent content launches, however. To resolve this issue, refer to the SAP Knowledge Base Article - [2169861](https://userapps.support.sap.com/sap/support/knowledge/en/2169861).

> [!NOTE]
> If the SSO on both Microsoft Entra ID and SAP SuccessFactors are already configured in the tenant, as described in the above documentation, then no action is required.
