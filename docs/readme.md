# GRAX : Engagement Manager
 
 ![GRAX : Engagement Manager](https://static.wixstatic.com/media/e58cbc_9a4653c845bb454f9b32aa2aa10767e5~mv2.png/v1/crop/x_0,y_3,w_800,h_345/e58cbc_9a4653c845bb454f9b32aa2aa10767e5~mv2.png "GRAX : Engagement Manager")
 

[GRAX : Engagement Manager](https://www.hardingpoint.com/grax) allows you to quickly ochestrate Salesforce data, customer engagement, 
device, backoffice, and app engagement. The [Engagement Graph](https://www.hardingpoint.com/grax) is used within the 
[GRAX : Engagement Manager](https://www.hardingpoint.com/grax) for deep analytics, artificial intelligence, reporting, and App 
Development. The more data and relationships you link with your [Engagement Graph](https://www.hardingpoint.com/grax) the 
quicker it builds, learns (via AI), and reacts (via Engagement Manager) from your [Neural Network](https://www.hardingpoint.com/grax).

* [`Engagement Manager`](https://engagementmanager.herokuapp.com) - <b>Instructions Below</b>
* [`Graf Connect`](https://graphconnect.hardingpoint.com/) - <b>Instructions Below</b>
* `Neural Network & AI` - Additional Package with your Engagement Graph
* `Analytics & Reporting` - Additional Package with your Engagement Graph

## Deployment & Configuration Instructions

1. [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

1. <a href="https://login.salesforce.com" target="_new">Login to Salesforce</a> or <a href="https://developer.salesforce.com/signup" target="_new">Create Salesforce Developer Edition</a> <i>(Right Click Open In New Tab)</i>

1. <a href="https://login.salesforce.com/lightning/switcher?destination=classic" target="_new">Switch to Salesforce Classic</a> <i>(Right Click Open In New Tab)</i>
        
1. <a href="https://login.salesforce.com/setup/ui/listCustomSettings.apexp" target="_new">Create a Salesforce Custom Setting</a> <i>(Right Click Open In New Tab)</i>
    1. Click `New` Salesforce.com Custom Setting 
        1. Label: `HardingPoint` 
        1. Object Name: `HardingPoint`
        1. Setting Type: `Hierarchy/Public`
        1. Visibility: Public
        1. Click `Save`
    1. Click `New` - Custom Field in HardingPoint Custom Setting
        1. Type `Text`
        1. Name: `ApiToken`
        1. Field Length: `255`
        1. Field Name: `ApiToken`
        1. Click `Next`
        1. Click `Save & New`
    1. Choose Type `Text` 
        1. Click `Next`
        1. Field Label: `GatewayToken`
        1. Length: `255`
        1. Field Name: `GatewayToken`
        1. Click `Next`
        1. Click `Save & New`
    1. Choose Type `Text` 
        1. Click `Next`
        1. Field Label: `LicenseToken`
        1. Length: `255`
        1. Field Name: `LicenseToken`
        1. Click `Next`
        1. Click `Save & New`
    1. Choose Type `URL`
        1. Click `Next`
        1. Field Label: `graphdburl`
        1. Field Name: `graphdburl`
        1. Click `Next`
        1. Click `Save`
