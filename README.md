# GoDaddy-dynamic-IP-host-update
Allows update dynamic machine's IP at Godady
Following code allows to update dynamic IP adress of your machine with Godaddy DNS, therefore removing the hassle of constantly updating your dynamic IP address. It also allows you not use free DNS services and call Godaddy API directly.
You can use it on Windows or Linux (bin/bash). 
1. Power Shell script - Windows
2. Bin/Bash - Linux.
For convenience you can package it as timed execution on Windows to run in the background or in Linux just set cron job. Alternatively you can tune TTL option.
For Windows dont forget to set PowerShell execution policy - Set-ExecutionPolicy -ExecutionPolicy Unrestricted
