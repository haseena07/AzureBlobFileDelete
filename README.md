# AzureBlobFileDelete
Delete Azure Blob file between a selected date range. This application is built using .net framework 4.5

Important:
Add Azure Blob Store Connection string and Container name in appsetting.config file.

Uncomment below line of Filter.cs class => method Iterates() => line 84
//await blobOperations.DeleteFile(fileName.Key);
