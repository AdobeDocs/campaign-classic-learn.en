---
title:  Tutorial Getting Started with push notifications for Android - Introduction
description: This tutorial will walk you through the steps involved in sending push notifications from Adobe Campaign and receiving these notifications in your Android app.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
---

# Tutorial Getting Started with push notifications for Android - Introduction

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

This tutorial will walk you through the steps involved in sending [!DNL push] notifications from Adobe Campaign to an [!DNL Android] app.

## Prerequisites

Before you can begin, you will need to fulfill the following prerequisites

1) Mobile application
This tutorial does not cover the detailed steps required to set up the mobile application. You will need to have an **[!DNL Android] mobile application with the [!DNL Campaign SDK]** integrated.

   * You can find a detailed description of the required steps in the [Integrating Campaign SDK into the mobile application](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html).

   * You can also use the Experience Platform Mobile SDK. FOr more information watch the [Configure the Push Channel using the Experience Platform Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) tutorial video.

2) Mobile App Channel package installed

    You will need to have the mobile app channel package installed on your instance. The following video explains how to check if the Mobile App channel is installed on your instance and if not, how to install it.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Tutorial

We would like to send a personalized promotional push notification to the subscribers of the Neotrip [!DNL Android] mobile app. The Neotrip app is configured with the Campaign SDK and we have made sure that the Mobile App channel is activated on our Campaign instance.

The following configuration steps are required:

### Step 1: Extend the app subscription schema to personalize push notifications

As we would like to personalize the push notification, we will first [extend the app subscription schema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) to be able to store the personalization values we receive from the app when the user subscribes to the service.

### Step 2: Configure the Android service and create the mobile app application in Campaign

Next we will need to [configure the Android service and create the mobile app application in Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). In this step we will define the Neotrip app as the target for the push notification.

### Step 3: Configure and send the push notification

Then we are ready to [configure and send the push notification](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## Start the tutorial

**[Step 1: Extend the app subscription schema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**
