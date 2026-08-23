`markdown
# LVM Lab

## Objective
Create and manage Logical Volumes using LVM.

## Commands Used
bash pvcreate /dev/nvme0n2
vgcreate soc_vg /dev/nvme0n2
lvcreate -L 1G -n logs-lv soc_vg
mkfs.ext4 /dev/soc_vg/logs-lv
mount /dev/soc_vg/logs-lv /soc_logs
lvextend -L +500M /dev/soc_vg/logs-lv
resize2fs /dev/soc_vg/logs-lv

## Results
- Created a Physical Volume
- Created a Volume Group
- Created a Logical Volume
- Mounted a filesystem
- Extended storage successfully

## Skills Learned
- LVM
- Storage Management
- Filesystem Administration
