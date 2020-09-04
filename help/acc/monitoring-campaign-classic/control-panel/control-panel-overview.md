---
title: Control Panel
seo-title: Control Panel
description: The Control Panel allows you to monitor and manage your SFTP storage by instance and allow list IP addresses.
seo-description: The Control Panel allows you to monitor and manage your SFTP storage by instance and allow list IP addresses.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
---

# [!UICONTROL Control Panel]

>[!NOTE]
>
>The terms ‘[!UICONTROL whitelist]’ and ‘[!UICONTROL blacklist]’ have been replaced by ‘[!UICONTROL allow list]’ and ‘[!UICONTROL block list]’in the Adobe Campaign documentation. 
>Some occurrences of these terms may still exist in the product UI, option names, internal code, as well as the tutorial videos. They will be replaced in upcoming Control Panel releases.

The [!UICONTROL Control Panel] allows Adobe Campaign administrators to monitor key assets and perform administrative tasks, such as managing the SFTP storage by instance or [!UICONTROL allow list] IP addresses.

## Accessing [!UICONTROL Control Panel]

To access the Control Panel go to Experience Cloud Home: [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**
  
  or
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **Campaign** > **[!UICONTROL Control Panel] card**
  
  or

* Directly from the URL: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Prerequisites

Before you get started, complete the following prerequisites:

### Confirm [!DNL IMS Org ID]

You need to know your [!DNL IMS org ID]. The following video describes where you can lookup your instance's [!DNL IMS org ID].

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Check [!DNL IMS Org ID] (00:26 min)*

### Administrator rights

Administrator rights are required to access to the [!UICONTROL Control Panel].
The following video explains how to add an administrator to a Campaign instance

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*How to add an administrator to the product profile "[!UICONTROL Administrators]" to be able to use [!UICONTROL Control Panel] (01:03 min)*

## [!UICONTROL Control Panel] tutorials

* **Managing SFTP servers**

    *Learn how to monitor the server capacity, [!UICONTROL allow list] IP addresses, and add SSH keys*

  * [Monitoring server capacity, allow listing IP addresses, and adding SSH keys](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Generating a SSH key](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Connecting to a SFTP server](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)
  
* **[Delegating subdomains](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

    *Learn how to fully delegate a subdomain to [!UICONTROL Adobe Campaign]*

* **[Adding SSL certificates](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

    *Learn how you can add a SSL certificates to secure your subdomains using Control Panel.*

* **[Adding URL permissions](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

    *how to add some outside URLs to the list of authorized URLs, so that your instance can connect to them.*

* **[Adding IP adresses to allow lists](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

    *Learn how to set up new connections to your instances by [!UICONTROL allow listing] IP addresses ranges.*

* **[Google TXT record management](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

    *Learn how to add [!DNL Google TXT] site verification record to all your subdomains used to send emails to [!DNL GMAIL] addresses through the [!UICONTROL Campaign Control Panel].*

* **GPG key management**

    *Learn how to generate and install a public/private key pair on a specified Campaign instance for the encryption of outbound data, as well as import and install a public key on a Campaign instance for the decryption of inbound data:*

  * [Generating and installing GPG keys for data encryption](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
  * [Using a GPG key to encrypt data](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
  * [Decrypting data](./gpg-key-management/decrypting-data.md)

* **[Troubleshooting the control panel](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

    *Understand how to troubleshoot the [!UICONTROL Control Panel]*

## Additional resources

* [Control Panel Help Center](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html)
