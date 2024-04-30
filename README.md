# Personal-IOS-XE
Python scripts for Cisco IOS-XE based devices (ASR, Catalyst, etc)

cdp_lldp.py: Use this on-box python script to display BOTH CDP and LLDP neighbors in a mixed vendor network. This script can be used on any Cisco IOS-XE that supports on-box python3 and is running both the LLDP and CDP process. 

To make things even easier, create a CLI alias to execute this python script and make it feel like a native CLI command.

Prerequisites: IOX enabled/guestshell with python3, cdp.lldp.py file is located in the bash home/user/guestshell directory 

CLI alias example: alias exec sh_nei guestshell run python3 cdp_lldp.py 

**Output:** 

![image](https://github.com/ShaunGomez/Personal-IOS-XE/assets/12215902/abcf1f53-6bb1-42c2-b713-91542452ef5f)
