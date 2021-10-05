# HANA DATABASE Restore Using SSM Automation Document


## Versions

Version | Author | Date   | Description   
--|---|---|--
  1.0|Ajay Kande  |  05 Oct 2021 | Initial Version, HANA single or distributed.  
  |   |   |  



## Description

This CloudFormation Template will deploy the SSM document which can be used to automate hana database restore.

For more details on its usage see the blog.


## Installation


1. In CloudFormation, select Create Stack and populate the required parameters or leave them as the defaults, ensuring that they are unique in your account. Select Next, then under configure stack options select Next, review the inputs and select Create Stack. Note: If you are redeploying this template, consider deleting old stacks.

<p align="center">
<img src="images/image-specify-stack-details2.png" alt="image-specify-stack-details" width=80%>
</p>

## Usage


Under Systems Manager > Documents > under “Owned by me” > Select the document with the name you specified and click on “Execute automation”. Familiarize yourself with the document by reading through the document and step descriptions.

Provide below input parameters to execute the restore

Option 1: Restore with BACKUP_ID 

<p align="center">
<img src="images/image-ssm-doc-descriptions.png" alt="image_ssm_doc_descriptions" width=80% >
</p>

Option 2: Restore with BACKUP_ID and Log Backups 


<p align="center">
<img src="images/image-ssm-doc-descriptions2.png" alt="image_ssm_doc_descriptions2" width=80% >
</p>

Click “Execute” and you can see the execution status in the next screen. Start time and End time of each step is displayed as shown below. 

Execution status for Restore with BACKUP_ID 

<p align="center">
<img src="images/image-ssm-execution-status2.png" alt="image-ssm-execution-status2" width=80% >
</p>

Execution status for Restore with BACKUP_ID and Log Backups 




***
