# Subnet IP Address Calculator
### subnet ip calculator in c++

With this calculator you can calculate network IP address by getting one of existing subnet IP addresses.

You can build it with command: 
g++ ipcalc.cpp -o ipcalc

**and then add it to your commands with:**

sudo cp ipcalc /usr/bin/

**Syntax of this is:**

ipcalc [OPTION]

**or:**

ipcalc [IP] [MASK]

**for the moment being there's only three options:**

-h or --help      Displays info about avaible options.

-i or --ip        You can input ip address after it.

-m or --mask      You can input mask address after it.



**example of usage:**

ipcalc -i 192.168.1.0 -m 255.255.255.0

ipcalc -m 255.255.255.0 -i 192.168.1.0


ipcalc 192.168.1.0 255.255.255.0

**YOU CAN'T SWAP THE MASK AND IP ADDRESS IN THE LAST EXAMPLE**
