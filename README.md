# DarkSheets
CTI, OSINT, Threat Hunting, Network and Web Recon, Discovery, Enumeration, Vulnerability Mapping, Exploitation, Reporting

# Get your Kali right!

Step 1

sudo su

sudo git clone https://github.com/aryanguenthner/365 /opt/365 && cd 365

chmod a+x *.sh *.py

chmod -R 777 /opt/365

sudo ./kali-setup.sh | tee kali.log

# Get your DarkSheets right!

Step 2

sudo su

sudo git clone https://github.com/aryanguenthner/ds /opt/ds && cd ds

chmod a+x *.sh *.py

chmod -R 777 /opt/ds

sudo ./darksheets-v1.2.sh | tee darksheets-v1.2.log
