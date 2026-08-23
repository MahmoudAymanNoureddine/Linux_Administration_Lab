
# Cron Jobs Lab

## Objective
Learn how to automate tasks using Cron.

## Commands Used
```
# bash
touch /tmp/test.log
crontab -e
*/1 * * * * echo "SOC LAB TEST" >> /tmp/test.log
cat /tmp/test.log
```

## Results
- Created a scheduled Cron job
- Automated command execution every minute
- Generated log entries successfully
- Verified task execution using log files

## Skills Learned
- Task Scheduling
- Linux Automation
- System Administration

## Lessons Learned
- Learned how to schedule automated tasks using Cron.
- Learned how to edit and manage cron jobs with the crontab command.
- Learned how recurring tasks can be used for monitoring and automation.
- Learned how to redirect command output to log files.
- Learned how to verify scheduled task execution through log inspection.
