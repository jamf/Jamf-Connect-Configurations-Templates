# Pre-configured Jamf Connect Configuration Templates
Channel partners of Jamf can use the Jamf Connect Evaluation Guide with Cloud Identity Providers made available and credentials supplied from Jamf.

The packages downloaded from the Evaluation Guide are ideal for use directly on a test Mac without the need for an MDM or any configurations to be applied.

With the included installer on this GitHub page in the releases section you can also get the available Cloud Identity Providers as templates in the Jamf Connect Configuration application., with this you can more easily customise the configuration and upload it directly to Jamf Pro or save it in `.plist` or `.mobileconfig` format to distribute it with any MDM

Make sure to read through the [Jamf Connect Evaluation Guide](https://docs.jamf.com/jamf-connect/evaluation-guide/index.html)

Currently Included:
* Azure
* OneLogin
* Google
* Okta

![](https://github.com/jamf/Jamf-Connect-Configurations-Templates/blob/main/images/JCC.png)

## Installation
::Warning: This overwrites existing configurations for Jamf Connect Configurations, If configurations for Jamf Connect Configuration already exist a back-up will be written to `/tmp`::

* **Required:** First install the latest Jamf Connect Configuration application. You can retrieve the installer through account.jamf.com or navigating to https://files.jamfconnect.com/JamfConnect.dmg
* Quit / Do not open Jamf Connect Configuration.
* Download and install the signed and notarized .pkg included in Releases which will distribute the templates in Jamf Connect Configuration.

## Please note that all resources contained within this repository are provided as-is and are not officially supported by Jamf.