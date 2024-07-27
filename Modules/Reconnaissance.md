# Reconnaissance

## Passive Reconnaissance

## Breached Credentials
## Hunting Subdomains
    • Tool - Sublist3r
    • Certificate fingerprinting - crt.sh
    • Owasp Amass
    •Http probe to verify the subdomain results
    
## Finding Frameworks
    • Builtwith.com
    • Wappalyzer
    • Whatweb ( kali tool)
    
## Information Gathering with Burp Suite
    • Target Enumeration using Burp
    
## Information Gathering with Google FU
    • Google dorks

## Social Media OSINT
    • Gathering information from company and user's social media profile

## Active Recon

## Nmap Scanning 
    • Stealth Scanning -sS
    • Nmap -T4 -p- -A <ip>
    
## Nikto 
    • Web Vulnerability Scanner
    • Command: nikto -h <hostname>
    
## Directory Enumeration tools 
    • Dirbuster
    • Gobuster 
    • Drib
    
## SMB Enumeration
    • Metasploit Auxilary Module to scan smb version
    • Smbclient
       • Smbclient -L \\\\<ip>\\ [List Share]
       • Smbclient \\\<ip>\\<ShareName>$
        
## SSH Enumeration
    • SSH <ip> 
    • SSH <ip> -oKexAlgorithms=+  -c cipher

## Searchsploit - Vulnerability Database