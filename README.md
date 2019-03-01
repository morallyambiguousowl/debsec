# debsec
startopsec is a script to run on login. 
This checks for security updates, upgrades, cleans, starts ProtonVPN, Privoxy, apparmor, ufw, shreds the clipboard, clears previously ran terminal commands. 

debset is a script in progress for the initial setup of Debian 9.
This script automates the process of installing:
1. apparmor
2. GNU MAC Changer
3. ufw(firewall)
4. protonvpn
5. privoxy
6. firejail (sandbox)
7. firetools (GUI for firejail)
8. Arpon (ARP Handling Inspection)
9. rkhunter (rootkit check)
10. SublimeText3

Place ssh_config in the /etc/ssh/ directory (Following STIGs)
Place sysctl.conf in the /etc/ directory for kernel hardening
