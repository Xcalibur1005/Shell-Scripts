# Shell-Scripts
This repository contains scripts for Penetration Testing written in Shell.

PING_SCANNER
This scripts uses "ping" function in shell to Ping Scan the subnet. It only works for "/24" subnet. It takes 3 Arguments as an input in 
the following format.
"./ping_scanner Subnet Start_IP_Range End_IP_Range"
Eg. ./ping_scanner 192.168.43 100 200

PORT_SCANNER
This script uses "/dev/tcp" package in Linux to find open ports. Initially it checks if IP is alive or not, and if it, it 
will perform Port Scan. It takes 3 Arguments as an input in the following format.
"./port_scanner IP_Address Start_Port_Range End_Port_Range"
Eg. ./port_scanner 192.168.43.150 20 1000 
