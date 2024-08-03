# Web Enumeration

## Assest Finder

    - go get -u github.com/tomnomnom/assetfinder

    - Assetfinder <target>
    - Assestfinder --subsl-only


Bash script to automate asset finder 

    #!/bin/bash

    url = $1 

    If [! -d "$url"]; then
        Mkdir $url
        
    Fi [ ! -d "$url/recon"]; then
        Mkdir $url/recon
    Fi

    Echo "[+] Harvesting subdomains with assetfinder"
    Assetfinder $url >> $url /recon/assets.txt
    Cat $url/recon/assets.txt | grep $1 >> $url/recon/final.txt
    Rm $url/recon/assets.txt

## Amass

    https://github.com/owasp-amass/amass/blob/master/doc/install.md

    - go install -v github.com/owasp-amass/amass/v4/...@master
    - Amass enum -d <url>

## Httpprobe
     
    - go install github.com/tomnomnom/httprobe@latest

## Gowitnes
    
    - go install github.com/sensepost/gowitness@latest
    - https://github.com/sensepost/gowitness/wiki/Installation 
    - Gotwitness single https://tesla.com
    

