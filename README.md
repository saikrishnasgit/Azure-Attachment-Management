# Azure-Attachment-Management
Attachment Management solution is an add-on feature to dynamics 365 CRM Online to manage notes and email attachments using Azure blob storage. Enables business users to optimize use of CRM Online storage and retrieve files on-demand through Dynamics CRM. It also offers additional optional feature of multiple files upload and download with a preview of the attachment. This solution is built on Dynamics 365 and seamlessly works on Dynamics CRM 2016 and above. Any suggestions/feedback from your end using Attachment Management would help us at Microsoft Labs to define the roadmap of this solution to its future. It would be ideal to test run the solution in your pre - production environments before installing in your production environment.
<br>
# What's New
Enhanced the functionality with Impersonation. Now the retrieve/retrieve multiple CRM service calls are getting created and called by SYSTEM instead of initiating user.
<br>
# How it works in Attachment Management 
Basically, Azure Attachment Management functionality (create attachments in blob, delete attachments in blob, retrieve attachments from blob) works only if the user who is having Least Permissions on “Azure Storage Settings” and “Notes Attachment Entity Settings” entities.
<br>
<br>
Now, with the impersonation…  users who are not even having the Least Permissions required to get Azure Attachment functionality can able to retrieve/download attachments from Azure. Because in the back-end the triggered event gets done the by SYSTEM “on behalf of the initiated user”.
<br>
## Download Managed CRM Solution
<br>
<a href="https://github.com/saikrishnasgit/Azure-Attachment-Management/raw/master/MicrosoftLabsAzuereBlobStorage_1_7_0_10_managed.zip" target="_blank">:file_folder:
</a>
