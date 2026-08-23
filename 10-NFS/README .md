
# NFS Lab

## Objective
Configure and manage Network File System (NFS).

## Commands Used
```
# bash
dnf install nfs-utils -y
systemctl enable --now nfs-server
mkdir /shared-data
exportfs -rav
showmount -e localhost
mount localhost:/shared-data /mnt/nfs-test
```

## Results
- Configured NFS Server
- Exported shared directory
- Mounted NFS share successfully

## Skills Learned
- NFS
- File Sharing
- Linux Network Services


## Lessons Learned
- Learned how to configure an NFS server.
- Learned how to export shared directories.
- Learned how to mount NFS shares.
- Learned how to verify exported resources.
- Learned how NFS enables file sharing across Linux systems.

