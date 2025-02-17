---
title: Manage custom and sideloaded apps 
author: ashishguptaiitb
ms.author: guptaashish
manager: prkosh
ms.topic: article
ms.tgt.pltfrm: cloud
ms.service: msteams
ms.subservice: teams-apps
audience: Admin
ms.collection: 
  - M365-collaboration
appliesto: 
  - Microsoft Teams
ms.localizationpriority: medium
search.appverid: MET150
description: Understand what are custom apps and sideloaded apps in Microsoft Teams and manage the apps to govern their behavior, rollout, and permissions.
f1.keywords:
- CSH
ms.custom: 
  - ms.teamsadmincenter.appsetuppolicies.overview
---

# Understand and manage custom and sideloaded apps

Microsoft Teams allows developers within your organization to build, test, and deploy custom apps for organization's internal users. Such apps are called custom apps or Line of Business apps. Your organization may commission the creation of custom apps for org-specific requirements. Admins control the rollout of and permissions for custom apps using various settings and policies.

:::image type="content" source="media/custom-app-orgwide-setting-trimmed.png" alt-text="Screenshot that shows how to allow custom apps in your organization in the org-wide settings panel." lightbox="media/custom-app-orgwide-setting.png":::

After you allow the use of a custom app, your end-users can find it by selecting **Built for your org** in the left navigation of Teams store.

:::image type="content" source="media/built-for-your-org1.png" alt-text="Screenshot of custom apps in Teams' store in the Teams' desktop app." lightbox="media/built-for-your-org2.png":::

## Understand sideloading of custom apps

When developing custom apps and before distributing those apps to the end-users, developers test the apps by adding it to Teams Store to test. The developers can test on their own or with a specified group of users, but the app isn't available to other end-users in the organization via the store. This method is called sideloading of apps and applies only to custom apps.

Developers can sideload an app to make it available to the members of a specific team, typically to test an under-development app. Using an app in this way limits its usage to the app developers and doesn't require admin approval as long as admin allows sideloading in Teams.

Developers can share a sideloaded app with a specific team without submitting it to the Teams app catalog. It makes the sideloaded custom app available to a limited group of end-users but not available in your organization's app store for all end-users.

As an admin, you can disallow sideloading of app for all developers. If you disallow sideloading, the developers can still test their apps by [creating a separate test tenant](/microsoftteams/platform/concepts/build-and-test/prepare-your-o365-tenant). Once custom app development is complete, developers request administrators to distribute their custom app to the end-users. For details, see [how to publish a custom app](/microsoftteams/upload-custom-apps). As an admin, you allow (or block) the use a custom app for all users or for specific users.

## Allow developers to upload custom apps

In app setup policy, you can create a custom policy or edit the global policy to allow uploading of custom apps. To create a custom policy and apply it to specific users, follow these steps:

1. Sign in to Teams admin center and access **Teams apps** > **[Setup policies](https://admin.teams.microsoft.com/policies/app-setup)**.
1. Select **Add**.
1. Provide a name and description for the policy.
1. Turn on or turn off **Upload custom apps**.
1. [Apply the policy to users](assign-policies-users-and-groups.md#assign-a-policy-to-individual-users) who develop custom apps and are allowed to upload those apps.

> [!NOTE]
> To change this setting, allow custom apps in the [org-wide app settings](manage-apps.md#manage-org-wide-app-settings).

## Related articles

* [Manage custom app policies and settings](teams-custom-app-policies-and-settings.md)
* [Understand policies to govern apps](app-policies.md)
* [Understand third-party apps](overview-third-party-apps.md)
