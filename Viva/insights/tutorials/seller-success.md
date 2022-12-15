---
ROBOTS: NOINDEX,NOFOLLOW
title: Seller success plan in Viva Insights 
description: Describes the seller success plan and how to create one 
author: madehmer
ms.author: helayne
ms.topic: article
ms.localizationpriority: medium 
ms.collection: viva-insights-advanced 
ms.service: viva 
ms.subservice: viva-insights 
search.appverid: 
- MET150 
manager: scott.ruble
audience: Admin
---

# Seller success plan

Sales departments are the most profitable for any company, but their effectiveness can be unpredictable because of the variability in how salespeople work. With this in mind, Viva Insights offers the seller success plan. Its purpose is to help sales organizations learn more about the behaviors that differentiate their most successful salespeople, and build plans that help salespeople acquire those behaviors.

It's not the purpose of the seller success plan to make sellers more productive simply by giving them more data. Rather, it aims to encourage sellers to reflect on how they use their limited time, and to make decisions that align their use of time with the company’s strategic priorities.

This plan displays insights to help salespeople optimally use their limited time to maximize productivity, conversion rates, and sales revenues. In this case, productivity is defined as spending more time with the right set of customers, building customer networks, and involving their manager and leadership in strategic customer meetings, as needed.

## Create a seller success plan

**Role** - Analyst or Limited analyst

**Prerequisite** - To create a seller success plan, you must have CRM data uploaded. For more information, see [CRM data](/viva/insights/setup/crm-data-upload?toc=/viva/insights/use/toc.json&bc=/viva/insights/breadcrumb/toc.json).

Complete the following tasks to create and run a seller success plan:

* [Create the plan](#create-the-plan) - Take the initial steps to create a plan.  
* [Select participants](#select-participants) - Select participants for the plan either by uploading a .csv file or by using filters.
* [Start the plan](#start-the-plan) - After the list of participants is validated, start the plan for them.

### Create the plan

1. Open [the advanced insights app](https://workplaceanalytics.office.com/). (If that link doesn't work, try [this link instead](https://workplaceanalytics-eu.office.com/).) If prompted, sign in with your work account.
2. Select **Plans**, and then for **Seller success**, select **Start now**.

    ![Plans main page.](../images/wpa/tutorials/solutions-main-page-w-highlight.png)

    The **Seller success plan** page opens: 

    ![New Seller success plan.](../images/wpa/tutorials/set-up-new-seller-plan.png)

3. Optionally, change the plan name from the default name.
4. Go to [Select participants](#select-participants).

### Select participants

If you have a particular group in mind, you can identify the group in either of the following ways:

* [Upload a .csv file](#upload-a-csv-file)  
* [Use filters](#use-filters)

#### Upload a .csv file

A **prerequisite** is to get a .csv file that lists the employees you want to participate in the plan. The format of this file is: a list of email addresses in a single column. To get this file, you might need it exported from an HR system by your HR manager or admin.

1. Get the .csv file (the prerequisite to this step).
2. Select **Upload .csv file**.
3. Select **Browse**, select a .csv file, and then select **Open**.
4. After the file has been uploaded, select **Validate**.

    The advanced insights app validates each potential participant and reports whether the group successfully validated, and it also displays any warnings that are generated. For more information, see [Validation](#validation).

5. After the group validates successfully and the number of participants meets or exceeds the minimum group size, you can proceed with the group that you selected. Go to [Start the plan](#start-the-plan).

#### Use filters

1. Select **Use filters**.
2. Add filters to define your group. For example, select **Organization**, **Equals**, and **Sales** in the fields to select the people who work in sales as your group. 

    Optionally, add more function types to expand this group, or add more filtering criteria to refine the selection: 

    ![Use filters to find group.](../images/wpa/tutorials/seller-plan-filters.png)

3. After you select the group(s) of participants, select **Validate**.
  
    The advanced insights app validates each potential participant and reports whether the group successfully validated, and it also displays any warnings that are generated. For more information, see [Validation](#validation).

4. After the group validates successfully and the number of participants meets or exceeds the minimum group size, you can proceed with the group that you selected. Go to [Start the plan](#start-the-plan).

### Start the plan

1. (Optional) Change the dates of the **Plan duration**. Do this by editing the start date of the plan.
2. Select **Create plan**. This starts the plan for the plan participants. For an overview of their experience, see [Participant experience](#participant-experience). 

## Task notes

### Validation

After you select **Validate**, the app checks for licenses of potential plan participants. Participants must have an applicable [Microsoft Viva Insights license](../personal/overview/plans-environments.md). If the user is missing either license, or has opted out of MyA, an error is generated and displayed for that user. That user is then removed from the list of potential plan participants. Validation results will only show the number of users for whom errors were found; no individual users are identified.

After the validation checks have run, if the final list of participants has enough people to meet or exceed the [minimum group size](/viva/insights/use/privacy-settings?toc=/viva/insights/use/toc.json&bc=/viva/insights/breadcrumb/toc.json#minimum-group-size) set for the organization, you can continue to use this group in creating your plan.

<!-- ADD THIS CONTENT AFTER THE TRACK PAGE APPEARS
Note: After you start the plan, you can end it by selecting the Stop button on the [what page is this? Show how to navigate there and what other actions you can take there] page. -->

<!-- Get FWLink to here for use in the product UI -->

## Participant experience

**Role** - No particular role is required. The only requirement is that participants have a Viva Insights license.

After a seller success plan starts, its participants receive a tailored email every month. It starts by summarizing how the salesperson spent their time in internal and external collaboration during the preceding month. The card displays the split between external and internal collaboration for people in similar roles; this information can help sellers compare their collaboration patterns with their peers. These numbers are calculated for all the participants in the plan.

![Email top.](../images/wpa/tutorials/email-top-70-30-new.png)

This email can contain any of several descriptive cards, each of which offers targeted suggestions to help participants work more effectively. The following sections describe these cards:

* [Time with customers](#time-with-customers)
* [Depth of engagement](#depth-of-engagement)
* [Manager interactions](#manager-interactions)

<!--* [Explore](#explore)-->
<!-- THIS ONE IS IN SECOND PERSON:

## Seller insights monthly email 

As a participant in a seller-success plan, you receive a monthly seller-insights email. It is meant to help you by streamlining your behavior in several aspects of sales success: time with customers, depth of engagement, internal networks, and connection with leadership. This mail starts out by summarizing how you spent your time in internal and external collaboration during the preceding month:
-->


 <!--  * [Leverage internal networks](#leverage-internal-networks) -->

<!-- In three of the cards, the **Suggestion** section contains **Explore** that the seller can select to learn more about this suggestion and how it can benefit them. -->
<!-- 
The last card, [Manager interaction](#manager-interaction), has a **Manage meetings** option. Selecting **Manage meetings** displays  upcoming meetings in the Outlook web calendar and, optionally, lets sellers make changes to those meetings.  --> 

### Time with customers

The _Time with customers_ card displays how sellers spent their time with  customers over the past month. Its chart reflects the following:

* The total **Collaboration hours** with each customer during the preceding month.  
* **Change %**: the change from the preceding month in collaboration hours for that account.

Its purpose is to help sellers decide whether they are spending time optimally with customers according to their respective potential.

![Time with customers.](../images/wpa/tutorials/time-with-customers-ss.png)

### Depth of engagement

The _Depth of engagement_ card shows the number of distinct people in the account with whom the seller had one or more [meaningful interactions](/viva/insights/use/glossary?toc=/viva/insights/use/toc.json&bc=/viva/insights/breadcrumb/toc.json#meaningful-interaction-define) in the last 28 days.

![Depth of engagement.](../images/wpa/tutorials/depth-of-engagement-ss.png)

### Manager interactions

Spending time with and getting attention from your manager is important for the success of salespeople. The chart on the _Manager interactions_ card displays the time the salesperson spent with their manager in meetings with particular customers.  

![Manager interactions.](../images/wpa/tutorials/manager-interactions-ss.png)

## Seller success Q & A

**Q1.** As a participant in a Seller success plan, what guidance will I receive to help me during my participation in the plan?  

A1. After the plan starts, you will regularly receive a tailored email. This mail starts out by summarizing how you spent your time in internal and external collaboration during the preceding month. For more information, see [Participant experience](#participant-experience).

**Q2.**  Why am I receiving this email?

A2. You receive the monthly "Seller insights" email so that you can visualize aspects of your sales-related behavior. The insights and suggestions in this email, which are based on recent collaboration with your customers and partners, can help you make course corrections with the goal of helping your sales productivity.
 
**Q3.** What can I do with the information in this email?

A3. It depends on the particular insight. For example, you can use the _Time with customers_ data to make large or small shifts in the amount of time you spend communicating with particular customers.
<!-- You can use the data in the _Leverage internal networks_ card to adjust the time that you spend communicating with particular internal groups&mdash;such as solution specialists&mdash;to a more appropriate level.
-->

**Q4.** This email contains charts that describe my workplace behavior. Where did this data come from?

A4. On a weekly basis, the advanced insights app receives from Microsoft 365 a copy of the preceding week's collaboration data about the emails, meetings, calls, and chats that took place. Also, the admins in your organization regularly upload two sets of data to the app: organizational data (descriptive data about employees), and CRM data (for example, customer account information, sales records, and purchasing history). The app then processes these data streams together to uncover the insights that it presents to you in the seller-insights email.

**Q5.** Who else can see this data about me?

A5. The data that you see in the seller insights email is your own data and only you have access to it. Your manager, your admin, and your teammates cannot see it. As is stated at the top of the email itself, this data is for your eyes only.

**Q6.** Could this data be used for other purposes?

A6. There is no mechanism or option that allows anyone but you to access your own personalized information that you receive within the email, unless you purposefully and independently share that information. The data and insights provided by this feature cannot be used for automated decision making or for profiling.
