---
title: "Manage and set up storyline in Viva Engage"
description: "Storyline empowers everyone within your organization to connect and contribute, while enabling your leaders to reach and engage employees."
ms.reviewer: ethli
ms.author: mamiejohnson
author: mamiepjohnson
manager: dmillerdyson
ms.date: 2/15/2023
audience: Admin
f1.keywords:
- NOCSH
ms.topic: article
ms.service: viva
ms.subservice: viva-engage
localization_priority: Priority
ms.collection:  
- M365initiative-viva
- highpri
search.appverid:
- MET150
---

# Manage and set up storyline in Viva Engage

Storyline empowers everyone within your organization to connect and contribute, while enabling your leaders to reach and engage employees. Through storyline, people can share updates, experiences, and perspectives to reach followers and colleagues across the organization. On storyline, there are two ways to share: posts and stories. Stories are short videos or photos that deliver a familiar, delightful way to catch up and stay connected with people across your organization. Engage with storylines from the Web and the mobile applications you use every day: Outlook, Microsoft Teams, and Microsoft Viva.

When storyline is enabled in your organization, you'll see the following changes in the Viva Engage app.

- Internal (non-guest) users who have access to Viva Engage see a new default **Storyline** tab on their user profile page.
- Users see a new **Storylines** page from which they can access a personalized feed of content posted to storyline, or toggle to a focused feed that includes only storyline content from the people the user has followed.

## Set up storyline

Microsoft 365 Global admin and Engage admin can manage storyline for their organizations in the [Engage admin center](/Viva/engage/eac-as-access-eac). Select the ellipses on the right of the top navigation menu, then select **Admin** to enter the Engage admin center.

![Image of the entrypoint into the Engage admin center.](/Viva/media/engage/admin/admin-entrypoint.png)

Under the **Feature management** tab within the Engage admin center, select **Storyline** to customize settings.

![Image of the entrypoint into managing storyline settings.](/Viva/media/engage/admin/storyline-eac-updated.png)

>[!NOTE]
> Storyline must be enabled before you can enable stories.

## Enable storyline

Once you're in the interface for managing storyline, admins will see toggles that control the availability of storyline within the organization. When storyline is enabled in your organization, it's available to all internal users who have access to Viva Engage. All internal users will have their own storyline feed on their profile page and will be able to see, react, and respond to others’ storyline posts.  

![Image of the storyline settings toggles in Viva Engage.](/Viva/media/engage/admin/storyline-toggle.png)

>[!NOTE]
> Guests won't have their own storyline and won't be able to see storyline content from the internal users who do have access.

When you disable storyline, it removes the **Storylines** tab from all user profile pages and removes the storylines landing page. Disabling storyline prevents new storyline conversations from starting, but does not delete any conversations that were posted prior to storyline being disabled. Previously posted storyline content can still be accessed through search and the Viva Engage Inbox by the people who participated in the storyline conversation. Users who didn't participate in the conversation won't have access after storyline has been disabled. Storyline content will continue to be available through network data export and will be available through eDiscovery for networks that are in native mode.  

## Enable stories

Storyline must be enabled before stories can be enabled. If storyline is disabled, stories will also be disabled and won't show up anywhere within the Viva Engage application. Stories are on by default unless storyline is disabled in your organization or you choose to toggle it off. If stories are disabled with storyline still enabled, the stories carousel on the home feed, storylines landing page, and on the users’ individual storyline pages will be removed. Disabling stories prevents new stories conversations from being started. Previously shared stories can still be accessed through Outlook and the Viva Engage inbox by people who participated in the story. Note that this follows the same behavior as storyline posts.

## Advanced Settings

Storyline supports additional controls for admins who wish to customize their configuration of storyline. Initially, this includes setting the default notification preferences for storyline, but we expect other advanced features to follow.

### Set default notification channels for Storyline posts

Storyline, in its default configuration, notifies followers via Teams, Email, and web, when a person they are following posts to their storyline. Network and Verified admins can override the network default with custom defaults for their organization. If you customize this for your network, it will change what default notifications are selected when a user follows someone. Users can always change from the default selections to their personal preferences for notifications for each person they follow.

The system default selections for notifications include:

- Microsoft Teams – notifications are delivered in the Teams Activity feed
- Email – email delivered to your Inbox includes support for Actionable messages, so the conversation can be viewed and replied from Outlook Web Access.
- Viva Engage – notifications are delivered to the Viva Engage notification bells.

## Security and compliance

Storyline is built on the same content and conversation platform as community messages in Viva Engage. This means that you can use the same tools for storyline that you use today for monitoring and governance.  

* eDiscovery through the compliance portal for native mode networks  
* Storyline content is available via network export
* Files shared through storyline are stored in OneDrive and are subject to any governance you already have in place
* Storylines supports the same [Report a conversation](/yammer/manage-yammer-groups/configure-conversation-reporting) feature available for community conversations
* Microsoft Purview Communications Compliance (E5): Use AI to monitor conversations for bullying, harassment, or topics that are against usage policy

In addition to the capabilities listed above, storyline also features a feed that includes all storyline posts sorted by the date the storyline conversation was started. To access this feed, go to the storyline landing page. While on the feed, select the filter icon in the upper right corner of the feed to switch the filter to **All**.

#### Security, compliance, and governance for files uploaded to storyline posts and stories

Storyline posts and stories are backed by Yammer services. Compliance for posts and stories is therefore the same as the rest of Viva Engage. If you are in native mode, posts are ingested into the substrate and support the same compliance and e-Discovery capabilities as posts in communities, including communications compliance and retention. Because files are stored in OneDrive, they inherit security and compliance policies configured for files in OneDrive.

When users are deleted—for example when an individual leaves the company—the system follows the Microsoft 365 user deletion process described in the **Delete a user** section in the [Manage Yammer users across their lifecycle from Office 365](/yammer/manage-yammer-users/manage-users-across-their-lifecycle) article.

## File storage for storyline

Files attached to storyline posts, and videos or photos shared as stories, are stored in a hidden library in the author’s OneDrive. While there is no entry point to this location in the user experience (UX) of Microsoft 365, you can access it with a URL resembling the following example: https://tenantname-my.sharepoint.com/personal/**useridentifier/VivaEngage/Attachments/Storyline**

You can determine the precise URL for a user's storyline folder by following these steps:

1. Open the user's OneDrive in the browser.
2. Note the URL to the user's OneDrive.
3. Locate the **user identifier**, located in the URL immediately after my.sharepoint.com/personal/
4. Remove everything after the profile identifier and the backslash, and replace with **VivaEngage** (without a space, case insensitive). The resulting URL will resemble this example: https://tenantname-my.sharepoint.com/personal/**useridentifier/VivaEngage**
5. Press ENTER. The library will appear.  
6. Open the Attachments folder, then open the storyline folder. The resulting URL directly to the folder where storyline files are saved will resemble this example: https://tenantname-my.sharepoint.com/personal/**user identifier/VivaEngage/Attachments/Storyline**.

### Managing files uploaded to storyline posts and stories

Edit documents and rich media uploaded to posts using the storyline interface. We strongly discourage you from managing (adding, replacing, or deleting) documents and rich media directly in OneDrive, as you will risk breaking the front-end experience of posts and stories in your storyline.  

If you wish to delete files associated with a post or story from the **VivaEngage** library:

1. Remove the file from the associated post. From any post, the author or an admin can select the ellipsis (...) menu and choose **Edit**.  
2. Navigate to the author's **VivaEngage** library and delete the file itself.

## Frequently Asked Questions (FAQ)

### Why isn’t storyline available in our organization? 
Storyline is only supported in Yammer enterprise networks that [enforce Office 365 identity](/yammer/configure-your-yammer-network/enforce-office-365-identity). If your network doesn't enforce Office 365 identity, or if you have a Yammer Basic network, storyline won't be available to your organization.

### Who can see storyline content? 
Storyline content is visible to any internal user who has access to Viva Engage. Guests won't be able to see any Storyline content.  

### Does storyline work for guests? 
Guests are excluded from storyline access. They won't have their own storyline, and won't be able to see any storyline content posted by other users.

### Can I control who sees storyline content? 
It isn't possible to prevent any internal user from seeing storyline content if they have access to Viva Engage. Guests won't be able to see any storyline content.

### Can I control which users get their own storyline?  
You can designate which users will have a personal storyline feed appear on their user profile page in Viva Engage through AAD groups. Users to whom you don’t grant a storyline will be able to reply and react to storyline posts from users who do have their own storyline.

### How do I delete custom cover photos that are uploaded to a person’s storyline? 
When the preview features toggle is in the ON position, uploaded cover photos can be deleted by the user themselves, or by Network and Verified Admins, by going to the user profile page and choosing the delete option under **Update cover photo**.

If you want to delete a previously uploaded cover photo when the preview toggle is in the OFF position, you will need to temporarily opt in to the preview so you can access the delete cover photo option as discussed above.

## See also

[Access the Engage admin center](/Viva/engage/eac-as-access-eac)

[Set up the Engage admin center](/Viva/engage/eac-get-started)

[Identify leaders and manage audiences in Viva Engage](/Viva/engage/leadership-identification)