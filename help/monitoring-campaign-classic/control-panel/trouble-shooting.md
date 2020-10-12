---
title: Trouble Shooting Control Panel
description: The Control Panel allows you to monitor and manage your SFTP storage by instance and allow list IP addresses.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
---

# Trouble shooting [!UICONTROL Control Panel]

## Login and Homepage

### Symptom: Unable to login to Experience Cloud

**What to do:**
The user needs to locate their IMS Org ID (xxx). The Administrator needs to add the user to the Product Profile “Campaign-xxx-Admins”  for each instance that they would like to manage. If the user is an admin of all instances they still might need to add themselves as users.

### Symptom: Links in the Experience Cloud Home to access [!UICONTROL Control Panel] do not appear for a user 

**Cause:**
Users won’t see the links until they are added as users to Product Profile _Campaign-xxx-Administrators/Admin_.

**What to do:**
The Administrator needs to add the user to the Product Profile _Campaign-xxx-Admins_  for each instance that they would like to manage. If the user is an admin of all instances they still might need to add themselves as “users. 

### Symptom: An Instance is not listed in the [!UICONTROL Control Panel]

**Cause:**
Most likely user needs to be added as a “user” Product Profile _Campaign-xxx-Administrators/Admin_ for the instance that is missing

**What to do:**
The Administrator needs to add the user to the Product Profile _Campaign-xxx-Admins_  for each instance that they would like to manage. If the user is an admin of all instances they still might need to add themselves as “users”.

### Helpful videos

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Check IMS Org ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*How to add an administrator to the product profile administrators to be able to use [!UICONTROL Control panel] (01:03 min)*

### Helpful Documentation

* [Discover the Control Panel](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [Managing permissions to the [!UICONTROL Control Panel]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## Establishing Connection to SFTP Server (Client or API)

Connecting to SFTP servers requires:

* [!UICONTROL Allow listing] the IP address from which you are connecting to the SFTP server  
* Private/public key pair that needs to be registered with Adobe Campaign
* If connecting to the SFTP server directly you will also need SFTP client software

### Helpful documentation

* [Logging into your SFTP server](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)
  