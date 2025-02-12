---
product-previous: workfront-fusion
product-area: workfront-integrations
navigation-topic: scenarios
title: Run the Scenario Scoring Expert in Adobe Workfront Fusion
description: The Scenario Scoring Expert can help you ensure that your scenario is configured in a way that follows best practices. It checks your scenario and gives recommendations for its structure and organization.
author: Becky
feature: Workfront Fusion
exl-id: 144c8dbd-a3e9-4267-b3db-0768dac8f384
---
# Run the Scenario Scoring Expert in Adobe Workfront Fusion

The Scenario Scoring Expert can help you ensure that your scenario is configured in a way that follows best practices. It checks your scenario and gives recommendations for its structure and organization.

## Access requirements

You must have the following access to use the functionality in this article:

<table style="table-layout:auto">  
 <col> 
 <col> 
 <tbody> 
  <tr> 
    <td role="rowheader">[!DNL Adobe Workfront] plan*</td> 
   <td> <p>[!DNL Pro] or higher</p> </td> 
  </tr> 
  <tr data-mc-conditions=""> 
   <td role="rowheader">[!DNL Adobe Workfront] license*</td> 
   <td> <p>[!UICONTROL Plan], [!UICONTROL Work]</p> </td> 
  </tr> 
  <tr> 
   <td role="rowheader">[!UICONTROL Adobe Workfront Fusion] license**</td> 
  <td> <p>[!UICONTROL [!DNL Workfront Fusion] for Work Automation and Integration] </p><p>[!UICONTROL [!DNL Workfront Fusion] for Work Automation] </p>  </td>    </tr> 
  </tr> 
  <tr> 
   <td role="rowheader">Product</td> 
   <td>Your organization must purchase [!DNL Adobe Workfront Fusion] as well as [!DNL Adobe Workfront] to use functionality described in this article.</td> 
  </tr> 
 </tbody> 
</table>

To find out what plan, license type, or access you have, contact your [!DNL Workfront] administrator.

For information on [!DNL Adobe Workfront Fusion] licenses, see [[!DNL Adobe Workfront Fusion] licenses](../../workfront-fusion/get-started/license-automation-vs-integration.md).

Run the Scenario Scoring Expert

1. Click the **[!UICONTROL Scenario]** tab in the left panel.
1. Select the scenario where you want to run the Scenario Scoring Expert.
1. Click anywhere on the scenario to enter the Scenario editor.
1. Click the Scenario Scoring Expert icon ![Scenario scoring expert](assets/scoring-expert-icon.png) near the bottom of the screen.

   The Scenario Scoring Expert panel opens.
1. Click **Evaluate**.

The Scenario Scoring Expert returns a score out of 10, and shows which checks have passed or failed. If a check has failed, the Scenario Scoring Expert gives recommendations for how to ensure that the scenario meets these checks.

![Scenario score](assets/scenario-score.png)

## Scenario scoring checks

The Scenario Scoring Expert uses the following checks:

* The scenario must be named.
* All modules must be labeled.
* The scenario must run on a set schedule.

   For instructions, see [Schedule a scenario](/help/quicksilver/workfront-fusion/scenarios/schedule-a-scenario.md).
* The scenario blueprint size must be under 5 MB.

   For more information, see [Fusion performance guardrails](/help/quicksilver/workfront-fusion/get-started/fusion-performance-guardrails.md#scenarios).
* If a Workfront instant trigger module is used, it must be filtered.
   
   For instructions, see [Event subscription filters in the [!DNL Workfront] > [!UICONTROL Watch Events] module](/help/quicksilver/workfront-fusion/apps-and-their-modules/workfront-modules.md#event-subscription-filters-in-the-workfront--watch-events-module).

