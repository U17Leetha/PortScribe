# PortScribe
Parse nmap output for open ports

## Description
Portscribe provides a quick glance at open ports from a plain text nmap scan. It will remove all additional information in the nmap output file and provide just the PORT, STATE, SERVICE, VERSION information. The intended purpose is for large nmap scans of subnets to reduce information overload and quickly identify low hanging fruit.  

## options
-o OUTPUT, --output OUTPUT     output file name

## example usage
    portscribe nmap_output.txt -o parsed_nmap.txt
