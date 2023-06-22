---
title: How to configure validation workflows in Adobe Campaign Classic
description: Learn how to configure different approval validation workflows.
feature: Workflows, Approvals
jira: KT-1566
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
---

# Create validation workflows

Adobe Campaign offers several options for marketers to review and provide delivery content, campaign target, data extraction, and budget approvals.

This tutorial explains how to configure different approval validation workflows.

## Prerequisite {#prerequisite}

Before enabling approval steps, the marketing team must define individual reviewers:

* The Adobe Campaign reviewer role within an approval activity can either be a single reviewer (Operator) or a group of reviewers (Operator role).
* To enable campaign developers to select the reviewers as approvers in a campaign or a delivery, the reviewers and reviewer groups must be configured in Adobe Campaign by an administrator.

## Configuring approvals for campaigns  {#configuring-approvals-for-campaigns}

 If you have the same set of reviewers for all deliveries in your campaign workflow, apply the campaign approval functionality, by setting up approvals and reviewers at the campaign level. The approval tasks and reviewers are pushed down to each delivery activity of your workflow once the workflow is executed.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12&learn=on)

## Configuring approvals for deliveries  {#configuring-approvals-for-deliveries}

You can also set up approvals at a delivery level. If delivery approvals steps and reviewers differ from the campaign approval steps and reviewers, the delivery settings override the campaign settings.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12&learn=on)

## Configuring an approval activity  {#configuring-an-approval-activity}

Unlike the delivery or campaign approvals, the approval activity allows one to create an approval process within a workflow. This way, the targeting selection logic can be approved before the delivery is launched. It also allows approval at multiple levels within the workflow, if needed.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12&learn=on)

For more information, refer to the [Approval Documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
