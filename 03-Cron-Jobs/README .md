`markdown
# Cron Jobs Lab

## Objective
Learn how to automate tasks using Cron.

## Commands Used
bash touch /tmp/test.log
crontab -e
*/1 * * * * echo "SOC LAB TEST" >> /tmp/test.log
cat /tmp/test.log

## Results
- Created a scheduled task
- Executed commands automatically
- Generated log entries successfully

## Skills Learned
- Task Scheduling
- Linux Automation
- System Administration
