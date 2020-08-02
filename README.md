# Exploit Title: eGroupWare 1.14 - 'spellchecker.php' Remote Command Execution
# Date: 2020-07-27
# Exploit Author: Berk KIRAS
# Vendor Homepage: https://www.egroupware.org/en/
# Version: 1.14
# Tested on: Apache
# Berk KIRAS PwC - Cyber Security Specialist 

#How to install?
$apt-get upgrade&&apt-get update
$git clone https://github.com/novanazizr/eGroupWare-1.14-RCE
$cd eGroupWare-1.14-RCE
$python3 exploit.py <target http/https> <IP>

#Requirement
1. python3
