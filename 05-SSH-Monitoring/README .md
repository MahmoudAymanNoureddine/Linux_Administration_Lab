
# SSH Monitoring Lab

## Objective
Learn how to monitor SSH activity and analyze authentication logs.

## Commands Used
```
# bash
systemctl status sshd
journalctl -u sshd
journalctl -xe
```

## Results
- Monitored SSH service status
- Observed successful logins
- Observed authentication failures
- Analyzed SSH related logs

## Skills Learned
- SSH Monitoring
- Log Analysis
- Linux Security
- Authentication Troubleshooting


## Lessons Learned
- Learned how to monitor SSH service activity.
- Learned how to identify successful login attempts.
- Learned how to detect authentication failures.
- Learned how to analyze SSH-related logs using system tools.
- Learned the importance of log monitoring in security operations.

## screenshots 
- sshd-service-status.png
- ssh-authentication-failure.png
- successful-ssh-login.png
