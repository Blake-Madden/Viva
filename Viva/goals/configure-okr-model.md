---
ms.date: 05/04/2022
title: Configure your OKR rules in Viva Goals
ms.reviewer: 
ms.author: rasanders
author: RaSanders-MSFT
manager: 
audience: Admin
f1.keywords:
- NOCSH
ms.topic: article
ms.service: viva
ms.subservice: viva-goals
ms.localizationpriority: medium
ms.collection:  
- m365initiative-viva-goals
- highpri  
search.appverid:
- MET150
description: "Learn how to configure your OKR rules in Viva Goals"
---

# Configure your OKR model in Viva Goals

Viva Goals understands that every business has its own set of processes and lets you create and configure your own OKR rules to fit your business needs. 

## How to configure your OKR rules 

1.	On the left panel in Viva Goals, select **Admin**.
1. In the **Admin Dashboard** section, select the **OKR Model Configuration** tab. 
2.	Define your objectives and key results (OKRs) and projects as described in the following sections.

### Define objectives

By default, objectives are defined as aspirational with measurable key results, which is the classic style for OKRs. Your objectives will record progress from 0 to 100 percent. By default, progress will be rolled up from key results, or you can choose to update progress manually. Your key results will have a metric associated with them.

Once you define your objectives as aspirational and key results as measurable, you can select the following options. 

#### Allow objectives to be nested under key results

Enable this option to nest your objectives under key results if your organization often defines metrics to drive that are large enough in scope to require a set of objectives.

#### Block objectives from contributing to the progress of their parent

Enable the **Block objectives** option if you don't want child objectives in your organization to contribute to the progress of their parents. Users can't override or edit the contribution settings.

> [!NOTE]
> Existing objectives that are already contributing to their parents will remain untouched. If you edit such objectives, the only option allowed would be to set the contribution to 0.

### Define key results 

#### Allow key results to be nested under key results.

Select this option if your organization often breaks down a key result's metrics into parts.

### Define projects

The **Projects** section covers project enablement, alignment, and contribution options.

#### Enable projects

Projects are the activities that drive toward your key results (your outcomes). Enable this option if you want projects reflected in your instance of Viva Goals.

- **Enable projects for specific users**

   Select this option if you want a few users in your organization to try out the projects feature before you roll it out more broadly. Only these specific users will be able to add projects. The projects created by these users will be visible to everyone. Search for and select the users that you want to enable projects for and save the list. 

- **Allow projects to be nested under key results**

   Select this option if you want users to be able to create projects focused on moving a single key result rather than the overall objective.

- **Define how projects should contribute**

   Select how projects should contribute to the progress of their parent:

   - Projects contribute to the progress of their parent by default.
   - Projects don't contribute to the progress of their parent by default.
   - Block projects from contributing to the progress of their parent.


## How to save your OKR model configuration settings

Select **Save** once you've chosen the settings that define your objectives, key results, and projects. The changes will take effect after select **Yes, Switch** in the confirmation pop-up dialog. 

> [!NOTE]
> Existing OKRs and Projects will remain untouched. Changes will be applied only to OKRs and projects created after the new settings are saved.

## How to customize the Objectives and Key Results progress bar 

Viva Goals offers a progress bar customization setting. This setting lets admins override the automatic scoring system. These setting can be found in the **OKRs & Projects** tab of the **Admin** dashboard. 

Viva Goals assesses progress in two ways: Actual and expected. By default, Viva Goals calculates the expected progress percentage based on the "Start date" and "End date" as specified by the user in the OKR. The actual progress is updated automatically via data integration or the roll-up of key results to an objective for auto-computed OKRs.

The default progress ranges within Viva Goals are:

- If the difference between expected progress and aggregate progress is greater than 25 percent, the status is mapped as **At Risk**.

- If the difference between expected progress and aggregate progress is between 0 percent and 25 percent, the status is mapped as **Behind**.

- If the difference between expected progress and aggregate progress is less than or equal to 0 percent, the status is mapped as **On Track**.

However, admins don't have to stick to these progress ranges. You can customize them based on the guidelines and policies in your organization.

