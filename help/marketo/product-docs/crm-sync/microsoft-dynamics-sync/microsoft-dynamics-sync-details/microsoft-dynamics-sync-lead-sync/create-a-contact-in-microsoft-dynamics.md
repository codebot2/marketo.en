---
unique-page-id: 10095389
description: Create a Contact in Microsoft Dynamics - Marketo Docs - Product Documentation
title: Create a Contact in Microsoft Dynamics
exl-id: 66cb26c0-f383-4d1e-be22-e7f8c6b266fb
---
# Create a Contact in Microsoft Dynamics {#create-a-contact-in-microsoft-dynamics}

1. Select the Marketo only person (Microsoft Type is empty) that you want to create as a contact in Dynamics.

   ![](assets/one.png)

1. Click **Person Actions** and **Microsoft**, and select **Sync Person to Microsoft**.

   ![](assets/two.png)

1. Click **Sync As** and select **Contact**. Click **Run Now**.

   ![](assets/three.png)

   >[!NOTE]
   >
   >When using the “Sync Person to Microsoft” flow action (in a trigger campaign only), the lead/contact will be created in real-time in Dynamics.

1. Marketo qualifies that Lead record in Dynamics into a Contact that is not associated to any Account in Dynamics.

   ![](assets/image2015-10-23-9-3a43-3a33.png)

1. Now, you can select **Contact** when you use the Sync As constraint in a smart campaign filter.

   ![](assets/five.png)
