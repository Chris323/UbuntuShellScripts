Steps required to have it run
1. Navigate to the directory it is saved in and please ensure you have made the file executable with chmod +x <filename>
2. Next ensure you have added your user name and shell command to the list of passwordless commands in sudo. This script contains a sudo command. Use sudo visudo, add
 username ALL=(ALL) NOPASSWD: /usr/bin/mysqldump at the bottom and save the buffer. Replace "username" with your account username.
3. Next to automate the task, you will be using cron.
