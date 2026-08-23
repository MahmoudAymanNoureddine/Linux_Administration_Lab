`markdown
# SELinux Lab

## Objective
Learn how SELinux contexts work and how to manage them.

## Commands Used
bash getenforce
sestatus
touch /tmp/security_test
ls -Z /tmp/security_test
chcon -t httpd_sys_content_t /tmp/security_test
restorecon -v /tmp/security_test

## Results
- Verified SELinux status
- Viewed file security contexts
- Modified SELinux context
- Restored default context

## Skills Learned
- SELinux
- Context Management
- Linux Security
