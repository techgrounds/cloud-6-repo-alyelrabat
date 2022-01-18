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

# Create an Azure file share

### Create a storage account via the Azure portal and select + Create a resource from the dashboard.

![image](https://user-images.githubusercontent.com/89514322/149903505-56207d38-54d7-488f-976d-46549d94def7.png)

### To create a FileStorage storage account, ensure the Performance radio button is set to Premium and Fileshares is selected in the Premium account type.

### After creating the FileStorage account, enable large files shares on an existing account.

<img width="1036" alt="Screen Shot 2022-01-18 at 10 15 29" src="https://user-images.githubusercontent.com/89514322/149907334-52c3508c-c913-4b18-a679-fa9e53e49411.png">




