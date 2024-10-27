# Some Potentially Dangerous Permissions

## General Dangerous Permissions
- *.ReadWrite
- *.FullControl
- *.Write
- *.Manage

## Other

### AppRoleAssignment.ReadWrite.All
- Grant additional privileges to itself or other applications
- Grant Admin Consent

### RoleManagement.ReadWrite.Directory
- Grant additional privileges to itself or other applications

### Directory.ReadWrite.All
- Read and write to the directory, equals Global Administrator rights

### User.ReadWrite.All
- Read and write full user profile
- Reset passwords

### Group.ReadWrite.All
- Read and write group properties
- Set Group Membership

### Application.ReadWrite.All
- Add new credentials to any other SP

### Sites.Read.All
- Read Sharepoint documents in all site collections

### Sites.ReadWrite.All
- Write Sharepoint documents to all site collections

### Sites.FullControl.All
- Full control in all site collections

### Mail.Read
- Read all mail boxes

... of course there might be more ;-)
