# Ditect-Connected-ip-to-linux

Run this command to find what the ip address are connected to ubuntu system

**netstat -ntu|awk '{print $5}'|cut -d: -f1 -s|sort|uniq -c|sort -nk1 -r**

it can be used to identify the ddos attack to linux server
