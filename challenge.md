## Question 1
Answer: I am dua-malik612. My home folder is /home/dua-malik612.
Commands: whoami, pwd (run after cd ~)

## Question 2
Answer: The server name is ubuntu. It runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release | head -2

## Question 3
Answer: The server has 1.6Gi of RAM in total. The root disk has 2.7G available (9.8G size, 72% used).
Commands: free -h, df -h /

## Question 4
Answer: root and dua-malik612 can log in with /bin/bash.
Commands: grep bash /etc/passwd

## Question 5
Answer: 245 lines were counted, so about 245 processes are running (the count includes the header line).
Commands: ps aux | wc -l

## Question 6
Answer: lab5user was created at 05:29:49 and deleted at 05:34:00 (UTC, 16 Oct 2026). An earlier broken attempt was created at 05:01:43 and removed at 05:29:35, because the first adduser was interrupted by an SSH disconnect.
Commands: sudo grep -E "new user|delete user" /var/log/auth.log
