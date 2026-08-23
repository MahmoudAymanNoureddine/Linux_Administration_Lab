
# Firewalld Lab

## Objective
Manage firewall rules and network access using Firewalld.

## Commands Used
```
# bash
firewall-cmd --list-all
firewall-cmd --get-active-zones
firewall-cmd --permanent --add-port=22/tcp
firewall-cmd --reload
firewall-cmd --list-ports
firewall-cmd --permanent --remove-port=22/tcp
firewall-cmd --reload
```
## Results
- Reviewed firewall configuration
- Opened a network port
- Reloaded firewall rules
- Removed firewall rule successfully

## Skills Learned
- Firewalld
- Port Management
- Linux Security


## Lessons Learned
- Learned how to manage firewall rules using Firewalld.
- Learned how to open and close network ports.
- Learned how to reload firewall configurations safely.
- Learned how to verify active firewall rules.
- Learned the importance of firewall management in Linux security.
