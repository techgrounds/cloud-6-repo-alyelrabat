# Azure Files

Azure Files can be used to completely replace or supplement traditional on-premises file servers or NAS devices.
Popular operating systems such as Windows, macOS, and Linux can directly mount Azure file shares.
With the Azure Files AD Authentication, SMB Azure file shares can continue to work with AD hosted on-premises for access control.
Azure file shares are deployed into storage accounts, which are top-level objects that represent a shared pool of storage. This pool of storage can be used to deploy multiple file shares.

## Key benefits

- Shared access
- Fully managed
- Script & tooling
- Resiliency
- Familiar programmability

https://docs.microsoft.com/en-us/azure/storage/files/storage-files-introduction?WT.mc_id=AZ-MVP-5003556

https://docs.microsoft.com/en-us/azure/storage/files/storage-files-quick-create-use-windows

https://docs.microsoft.com/en-us/azure/storage/files/storage-files-planning

# Azure File Sync

Azure File Sync allows you to extend your on-premises file shares into Azure. It works with your existing on-premises file shares to expand your storage capacity and provide redundancy in the cloud.
You can access your on-premises file share with any supported file sharing protocol that Windows Server supports, like SMB, NFS, or FTPS.
As for now it requires Windows Server 2012 R2 or later.

![image](https://user-images.githubusercontent.com/89514322/150013444-45aa25d6-cbc2-4df4-8469-6863f7b8cc73.png)

The diagram shows what happens when a user requests two files. File A is used frequently, so the entire file is available on the local file share. File B isn't used often, so the file is retrieved from the Azure file share.

https://docs.microsoft.com/en-us/learn/modules/extend-share-capacity-with-azure-file-sync/2-what-azure-file-sync

# Azure / Storage / Files

### Create a storage account via the Azure portal and select + Create a resource from the dashboard.

![image](https://user-images.githubusercontent.com/89514322/149903505-56207d38-54d7-488f-976d-46549d94def7.png)

### Create a file share

<img width="1437" alt="Screen Shot 2022-01-18 at 14 32 07" src="https://user-images.githubusercontent.com/89514322/149946873-8ea7ce21-61cb-4fa1-b59a-ebcad5b103da.png">

# Create an SMB file share 

### Create a File Storage account via the Azure portal and select + Create a resource from the dashboard.

