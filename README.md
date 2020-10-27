Getting Started with Azure Automation - Get Azure VMs using AD Authentication
=============================================================================

            

**Description**


This runbook sample demonstrates how to connect to Azure using organization id credential based authentication.  It connects to Azure and retrieves the names of all VMs in the specified Azure subscription. 


You can find more information on configuring Azure so that Azure Automation can manage your  Azure subscription(s) here:
[http://aka.ms/Sspv1l](http://aka.ms/Sspv1l)


After configuring Azure and creating the Azure Automation credential asset, make sure to update this runbook to contain your Azure subscription name and credential asset name.


**Requirements**


Before running this runbook, make sure the following components are available:


  *  Azure Active Directory user with permissions to manage the Azure subscription you want to work against. 

  *  An Azure Automation credential asset containing the user's username / password.


**Runbook Contents**


The runbook's contents are displayed below:


 

 

 


 



        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
