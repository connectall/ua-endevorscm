# ua-endevorscm

The EndevorSCM Universal Adapter is developed as an extension to the universal adapter capability of ConnectALL. This adapter will allow the user to listen events from Element and Package actions with ConnectALL. Current capabilities and limitations are defined below.

Please refer to the [ConnectALL Tech Docs](https://techdocs.broadcom.com/us/en/ca-enterprise-software/valueops/connectall/3-6/adapters/universal-adapter.html) for more information.

If you are an existing SaaS customer, please contact Broadcom Support to enable the adapter in your environment. If you are using ConnectALL On-Premise, you may download and install this adapter in your environment. If you are not yet a customer, [please reach out to learn more](https://enterprise-software.broadcom.com/contact-us).

# Setup

## Supported Entities

This Universal Adapter currently supports the following entities:
* Elements
* Packages

*Note: This Universal Adapter is provided as-is. It is tested and validated using the entities and configurations as defined. Any additional customizations are not supported and should be made at your own discretion.*

## Connection Details

* **Connection Name:** *Name of Application*
* **Application Type:** EndevorSCM
* **URL:** value to access EndevorSCM Wehbook Server (ie: https://endevor-webhooks-server.broadcom.com)
* **User Name:** login user account
* **Password:** Leave Blank
* **Application Category:** *Pick from dropdown list*
* **Time Zone:** Leave Blank
* **Select Group:** *Set if neccessary*


## Flow Filters

Flow Filters are not used for this adapter.

## Example Automation

EndevorSCM Events on Items (Elements, etc) that are created or updated will be sent through the Universal Adapter to a receiving application containing the set fields valued. 

# Known Limitations

Available fields are limited to what is setup by the Fields values.  
