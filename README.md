# Azure-Attachment-Management
Attachment Management solution is an add-on feature to dynamics 365 CRM Online to manage notes and email attachments using Azure blob storage. Enables business users to optimize use of CRM Online storage and retrieve files on-demand through Dynamics CRM. It also offers additional optional feature of multiple files upload and download with a preview of the attachment. This solution is built on Dynamics 365 and seamlessly works on Dynamics CRM 2016 and above. Any suggestions/feedback from your end using Attachment Management would help us at Microsoft Labs to define the roadmap of this solution to its future. It would be ideal to test run the solution in your pre - production environments before installing in your production environment.
<br>
# What's New?
Enhanced the functionality with Plug in Impersonation. Now without Least Permissions on "Azure Attachment Management" entities to trigger blob events user can able trigger blob events (create/update/delete blobs).
<br>
# How *impersonation* change, effects Attachment Management 
Azure Attachment Management functionality (create attachments in blob, delete attachments in blob, retrieve attachments from blob) works only if the user who is having Least Permissions on “Azure Storage Settings” and “Notes Attachment Entity Settings” entities.
<br>
<br>
Now, with the impersonation  users who are not even having the Least Permissions required to get Azure Attachment functionality can able to retrieve/download attachments from Azure. This is been taken care by the impersonation change, which runs the plugins on OOB SYSTM user context.
<br>
## Download CRM Managed Solution <a href="https://github.com/saikrishnasgit/Azure-Attachment-Management/raw/master/MicrosoftLabsAzuereBlobStorage_1_7_0_11_managed.zip" target="_blank">here</a>
<br>
