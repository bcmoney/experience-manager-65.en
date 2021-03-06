---
title: Check in and check out your digital assets for editing
description: Learn how to check out assets for editing and check them back in after the changes are complete.
contentOwner: AG
---

# Check-in and check-out files in Experience Manager DAM {#check-in-and-check-out-files-in-assets}

Adobe Experience Manager Assets lets you check out assets for editing and check them back in after you complete making the changes. After you check out an asset, only you can edit, annotate, publish, move, or delete the asset. Checking out an asset locks the asset. Other users cannot perform any of these operations on the asset until you check the asset back in to Assets. However, they can still change the metadata for the locked asset.

To be able to check out/in assets, you require Write access on them.

This feature helps prevent other users from overriding the changes made by an author where multiple users collaborate on editing workflows across teams.

## Check out assets {#checking-out-assets}

1. From the Assets UI, select the asset you want to check out. You can also select multiple assets to check out.
1. From the toolbar, click **[!UICONTROL Checkout]**.
    The **[!UICONTROL Checkout]** option toggles to **[!UICONTROL Checkin]**.
    To verify whether other users can edit the asset you checked out, log in as a different user. A lock symbol displays on the thumbnail of the asset that you checked out.

   ![chlimage_1-471](assets/chlimage_1-471.png)

   Select the asset. Notice that the toolbar does not display any options that let you edit, annotate, publish, or delete the asset.

   ![chlimage_1-472](assets/chlimage_1-472.png)

   You can click **[!UICONTROL View Properties]** to edit the metadata for the locked asset.

1. Click **[!UICONTROL Edit]** to open the asset in edit mode.

   ![chlimage_1-473](assets/chlimage_1-473.png)

1. Edit the asset and save the changes. For example, crop the image and save.

   ![chlimage_1-474](assets/chlimage_1-474.png)

   You can also choose to annotate or publish the asset.

1. Select the edited asset from the [!DNL Assets] interface, and click **[!UICONTROL Checkin]** from the toolbar. The modified asset is checked in to Assets and is available to other users for editing.

## Forced check in {#forced-check-in}

Administrators can check in assets that are checked out by other users.

1. Log in to Assets as an administrator.
1. From the Assets UI select one or more assets that have been checked out by other users.

   ![chlimage_1-476](assets/chlimage_1-476.png)

1. From the toolbar, click **[!UICONTROL Release Lock]**. The asset is checked back in and available for edit to other users.

>[!MORELIKETHIS]
>
>* [Understand check in and check out in Experience Manager desktop app](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/using.html#how-app-works2)
>* [Video tutorial to understand check in and check out in Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/checkin-checkout-technical-video-understand.html)
