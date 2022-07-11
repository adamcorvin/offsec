create a top level directory
create a flat file titled: passwords, users, and hashes
create a folder for files, vulns



    export IP="192.168.1.100"
    explort URL="http://192.168.1.100/"
    
    echo $IP
    
    echo $URL
    
    nmap -p- -sC -sV $IP --open
    
    nikto --host $URL -C all
    
    enum4linux -A $IP

###SMB NULL SESSION (discovered during enun4linux

    smbclient //'IPADDRESS'/DIRECTOR -N 






apt install seclists , it will normally be located at /usr/share/Seclists/....






