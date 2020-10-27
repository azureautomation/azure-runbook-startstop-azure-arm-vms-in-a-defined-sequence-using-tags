Azure Runbook - Start-Stop Azure ARM VMs in a defined sequence using Tags
=========================================================================

            

 


This Azure Runbook Workflow helps to Start/Stop VMs in Azure ARM portal in a defined sequence using Tags


To onboard servers, simply add a Tag named 'AutoStart' with a Json formatted value in the form {'Group':'1','Sequence':'2'}


You can target individual GROUPS or ALL VMs in the subscription and Start/Stop them in defined sequence.


START is performed in Ascending order of sequence 1.2.3.. and during STOP sequence is reversed 3..2..1


Parameters allows you to customize Tags and Values further.


 


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
