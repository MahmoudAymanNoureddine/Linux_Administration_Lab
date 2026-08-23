`markdown
# NFS Lab

## Objective
Configure and manage Network File System (NFS).

## Commands Used
bash dnf install nfs-utils -y
systemctl enable --now nfs-server
mkdir /shared-data
exportfs -rav
showmount -e localhost
mount localhost:/shared-data /mnt/nfs-test

## Results
- Configured NFS Server
- Exported shared directory
- Mounted NFS share successfully

## Skills Learned
- NFS
- File Sharing
- Linux Network Services
