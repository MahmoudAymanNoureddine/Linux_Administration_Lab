
# ACL Lab

## Objective
Learn how to manage Access Control Lists (ACLs) in Linux.

## Commands Used
```
# bash
mkdir /soc_lab
setfacl -m u:analyst1:rwx /soc_lab
getfacl /soc_lab
```
## Results
- Created a shared directory
- Granted analyst1 full access
- Verified ACL configuration

## Skills Learned
- Access Control Lists (ACL)
- File Permissions Management
- Linux Security Basics


## Lessons Learned
- ACLs provide more flexible permissions than traditional Linux permissions.
- Specific users can be granted access without changing ownership or group membership.
- ACL configurations can be verified using the getfacl command.
- ACL entries can be modified using the setfacl command.
- Fine-grained access control improves Linux security and administration.
