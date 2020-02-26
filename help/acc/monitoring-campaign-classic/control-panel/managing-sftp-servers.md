---
title: Managing SFTP Servers
seo-title: Managing SFTP Servers
description: The Control Panel allows you to monitor and manage your SFTP storage by instance and whitelist IP addresses.
seo-description: The Control Panel allows you to monitor and manage your SFTP storage by instance and whitelist IP addresses.
feature: SFTP Server Whitelisting
topics: ACC Control Panel
kt: KT-3266
doc-type: feature video
activity: use
team: PM
---

# Managing SFTP Servers {#cp-managing-sftp-servers}

## Working with the Control Panel: Monitoring server capacity, whitelisting IP addresses, and adding SSH keys

To access the Control Panel go to Experience Cloud Home: [https://experiencecloud.adobe.com]( https://experiencecloud.adobe.com):

* Experience Cloud Home > Quick Access
  or
* Experience Cloud Home > Solution picker: Campaign > Control Panel card
  or
* Directly from the URL: `https://your_instance_URL/campaign/controlpanel`

>[!VIDEO](https://video.tv.adobe.com/v/27270?quality=12)
*This video explains how to access the Adobe Campaign Control Panel, monitor the storage of SFTP servers, whitelist an IP, as well as add an SSH Key (04:07 min)*

>[!NOTE]
>
>**Instances:** Only the instances for which you have administrator rights will be listed. 
>
>**Job Logs:** Only jobs that were executed in the control panel are listed. The jobs that were executed outside of Control Panel are not included (for example workflows being executed, etc.)
>
>The logs only include the jobs executed by the administrators of your Org. If there are several Orgs, you won't see the logs of other orgs in the Job Logs
>
>**Storage Tab:** The header shows the top three most utilized servers, if you have more than 3 servers you can see the rest in the Storage tab
>
>**Warning message:**
>
>Orange - the server is 80% utilized
>
>Red - the server is 90% utilized 

## Generate SSH Key

You need to be able to generate a SSH key. The video below explains how to generate a SSH key using a terminal.

>[!VIDEO](https://video.tv.adobe.com/v/27259?quality=12)
*How to create a SSH key (2:16 min)*

## Connect to a SFTP Server

Connecting to SFTP servers requires:

* Whitelisting the IP address from which you are connecting to the SFTP server  
* Private/public key pair that needs to be registered with Adobe Campaign
* If connecting to the SFTP server directly you will also need SFTP client software

>[!VIDEO](https://video.tv.adobe.com/v/27263?quality=12)
*Connect to a SFTP server (02:04 min)*
