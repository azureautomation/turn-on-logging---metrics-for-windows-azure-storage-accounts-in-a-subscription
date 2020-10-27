Turn On Logging &amp; Metrics for Windows Azure Storage Accounts in a Subscription
==================================================================================

            

[Windows Azure Scripting Center](http://www.windowsazure.com/en-us/documentation/scripts) |
[Get Started with Windows Azure PowerShell](http://go.microsoft.com/fwlink/?linkid=320929&clcid=0x409) |
[Windows Azure Data Management Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=data-management&service=all)

Description

Sets storage logging and metrics settings on storage accounts in the current subscription. Settings can be enable or disabled.


**Note:** This script requires an Azure Storage Account to run. The storage account can be specified by setting the subscription configuration. For example,


Set-AzureSubscription -SubscriptionName 'MySubscription' -CurrentStorageAccount 'MyStorageAccount'

Example
 
Scenario
You want to enable or disable logging and/or metrics on one or more storage accounts in a subscription.
Requirements

  *  PowerShell Version 3.0 
  *  Windows Azure PowerShell 0.6.18 
See Also

  *  [Set-AzureSubscription](http://msdn.microsoft.com/en-us/library/windowsazure/dn408531.aspx)

  *  [Windows Azure Data Management Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=data-management&service=all)

Script Content

The content of the script is reproduced below

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
