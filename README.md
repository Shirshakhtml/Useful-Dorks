<h2 align="center">Useful Dorks</h2>
  <p align="center">
    <a
      href="https://github.com/Shirshakhtml/Useful-Dorks/issues/new?assignees=&labels=bug">Report
      Issue</a>
      <-->
    <a href="https://github.com/Shirshakhtml/Useful-Dorks/issues">Add Dork</a>
  <br><br>
  
  <img alt="Osint-tool" src="https://img.shields.io/github/stars/Shirshakhtml/Useful-Dorks">
  <img alt="Osint-tool" src="https://img.shields.io/github/issues/Shirshakhtml/Useful-Dorks">
  <img alt="Osint-tool" src="https://img.shields.io/github/languages/code-size/Shirshakhtml/Useful-Dorks">
  </p>
  <br>
  
  ***P.S- I have personally tested out these dorks***
  
  
  ## Github Dorks
  
  1.*"domain.com" security_credentials* : **LDAP(Active Directory) credentials**<br>
  2.*"domain.com" connectionstring* : **Database Credentials**<br>
  3.*"domain.com" JDBC* : **Database Credentials**<br>
  4.*"domain.com" ssh2_auth_password* : **Unauthorized access to Servers**<br>
  5.*"domain.com" send_keys or send,keys* : **LDAP(Active Directory) credentials**<br>
  5.*"domain.com" Sensitive Data* : **Sensitive Information**<br>
  5.*"domain.com" password* : **Passwords**<br>
  5.*"domain.com" dbpassword* : **Database Passwords**<br>
  5.*"domain.com" dbuser* : **Database User Names**<br>
  5.*"domain.com" access_key* : **Access Key Credentials**<br>
  5.*"domain.com" secret_access_key* : **Access Key Credentials**<br>
  5.*"domain.com" bucket_password* : **Cloud Bucket credentials**<br>
  5.*"domain.com" redis_password* : **Redis Passwords**<br>
  5.*"domain.com" root_password* : **Root Password**<br>
  5.*"domain.com" HOST=smtp.gmail.com* : **SMTP Sensitive Information**<br>
  5.*"domain.com" filename:.htpasswd* : **Wordpress File to store Username and Password**<br>
  5.*"domain.com" extension:sql mysql dump* : **MYSQL Dump Information**<br>
  
  ## Google Dorks
  
  ## PS
>In case of different subdomains or according to your scope you can put * on that place i.e **.domain.com or subdomain.domain.** in place of "site" in the dorks given below.

  1.*site:domain.com intitle:"index of" "/configs"* : **Configuartion Files**<br>
  2.*site:domain.com allintext:username filetype:log* : **Log Files**<br>
  3.*"site:domain.com" inurl:/proc/self/cwd* : **Vulnerable Web Server**<br>
  4.*"site:domain.com" intitle:"index of" inurl:ftp* : **Open FTP Server**<br>
  5.*"site:domain.com" intitle:"index of" inurl:env* : **Env Files**<br>
  6.*"site:domain.com" intitle:index.of id_rsa -id_rsa.pub* : **SSH private keys**<br>
  7.*"site:domain.com" filetype:xls inurl:"email.xls”* : **Email lists**<br>
  8.*"site:domain.com" "index of" "database.sql.zip”* : **SQL Database Dumps**<br>
  9.*"site:domain.com" intitle:"Index of" wp-admin* : **WordPress Admin**<br>
  9.*"site:domain.com" intitle:"Apache2 Ubuntu Default Page: It works”* : **Apache2**<br>
  9.*"site:domain.com" "Index of" inurl:phpmyadmin* : **PHPmyadmin**<br>
  9.*"site:domain.com" inurl:Dashboard.jspa intext:"Atlassian Jira Project Management Software"* : **JIRA**<br>
  9.*"site:domain.com" inurl:app/kibana intext:Loading Kibana* : **Kibana**<br>
  
  ## Sensitive Dorks
  1.*"site:domain.com" intitle:"index of" "WebServers.xml"* : **XML configuration file for Webserver Running**<br>
  2.*"site:domain.com" filetype:xls inurl:"email.xls"* : **Excel file containing emails, can display Company's internal member's emails **<br>
  3.*"site:domain.com" intitle:"Index of" wp-admin* : **WordPress Admin**<br>
  4.*"site:domain.com" intitle:"index of" "admin/sql/"* : **SQL Database Files**<br>
  5.*"site:domain.com" intitle:"index of" "system/config"* : **System Configuration Files**<br>
  6.*"site:domain.com" index of /wp-content/uploads/* : **WordPress Uploaded Files**<br>
  7.*"site:domain.com" intext:"index of" "var/log/"* : **Logged Messages which can be cron jobs, daemon processes, kernel and auth logs**<br>
  8.*"site:domain.com" intitle:"Dashboard [Jenkins]"* : **Open Jenkins Dashboard**<br>
  9.*"site:domain.com" intitle:"index of" "shell.php"* : **Check for any Uploaded Shell**<br>
  
  ## Open Redirect Dorks
  
1. site:domain.com /{payload}
2. site:domain.com ?next={payload}
3. site:domain.com ?url={payload}
4. site:domain.com ?target={payload}
5. site:domain.com ?rurl={payload}
6. site:domain.com ?dest={payload}
7. site:domain.com ?destination={payload}
8. site:domain.com ?redir={payload}
9. site:domain.com ?redirect_uri={payload}
10. site:domain.com ?redirect_url={payload}
11. site:domain.com ?redirect={payload}
12. site:domain.com /redirect/{payload}
13. site:domain.com /cgi-bin/redirect.cgi?{payload}
14. site:domain.com /out/{payload}
15. site:domain.com /out?{payload}
16. site:domain.com ?view={payload}
17. site:domain.com /login?to={payload}
18. site:domain.com ?image_url={payload}
19. site:domain.com ?go={payload}
20. site:domain.com ?return={payload}
21. site:domain.com ?returnTo={payload}
22. site:domain.com ?return_to={payload}
23. site:domain.com ?checkout_url={payload}
24. site:domain.com ?continue={payload}
25. site:domain.com ?return_path={payload}
  
## Shodan Dorks

1. "default password" org:Organization Name
2. "230 login successful" port:"21" org:Organization Name
3. vsftpd 2.3.4 port:21 org:Organization Name
4. 230 'anonymous@' login ok org:Organization Name
5. guest login ok org:Organization Name
6. country:EU port:21 -530 +230 +Organization Name
7. country:IN port:80 title:protected org:Organization Name
8. net: IP_ADDR product:elastic
9. net: IP_ADDR port:9200 user
10. port:"9200" all:''elastic indices
11. port:27017 -all:"partially" all:''fs.files
  
# Shodan Dorks for the following:
  - Industrial Control System(ICS)
  - Remote Desktop
  - Network Infrastructure
  - Network Attached Storage
  - Webcams
  - Printers
  - Home Devices
  - Random Stuff

**ICS**
1. "Server: Prismview Player" : ICS
2. "in-tank inventory" port:10001 : Gas Station Pump Controller
3. P372 "ANPR enabled" : Automatic License Plate Readers
4. mikrotik streetlight : Traffic Light Controllers / Red Light Cameras
5. "voter system serial" country:US : Voting Machines in the United States
6. "Cisco IOS" "ADVIPSERVICESK9_LI-M" : Telcos Running Cisco Lawful Intercept Wiretaps
7. "[2J[H Encartele Confidential" : Prison Pay Phones
8. http.title:"Tesla PowerPack System" http.component:"d3" -ga3ca4f2 : Tesla PowerPack Charging Status
9. "Server: gSOAP/2.8" "Content-Length: 583" : Electric Vehicle Chargers
10. "Cobham SATCOM" OR ("Sailor" "VSAT") : Maritime Satellites
11. title:"Slocum Fleet Mission Control" : Submarine Mission Control Dashboards 
12. "Server: CarelDataServer" "200 Document follows" : CAREL PlantVisor Refrigeration Units
13. http.title:"Nordex Control" "Windows 2000 5.0 x86" "Jetty/3.1 (JSP 1.1; Servlet 2.2; java 1.6.0_14)" : Nordex Wind Turbine Farms
14. "[1m[35mWelcome on console" : C4 Max Commercial Vehicle GPS Trackers
15. "DICOM Server Response" port:104 : DICOM Medical X-Ray Machines
16. "Server: EIG Embedded Web Server" "200 Document follows" : GaugeTech Electricity Meters
17. "Siemens, SIMATIC" port:161 : Siemens Industrial Automation
18. "Server: Microsoft-WinCE" "Content-Length: 12581" : Siemens HVAC Controllers
19. "HID VertX" port:4070 : Door / Lock Access Controllers
20. "log off" "select the appropriate" : Railroad Management

**Remote Desktop**
1. "authentication disabled" "RFB 003.008" : Unprotected VNC 
2. "\x03\x00\x00\x0b\x06\xd0\x00\x00\x124\x00" : Windows RDP
3. title:"Weave Scope" http.favicon.hash:567176827 : Weave Scope Dashboards
4. "MongoDB Server Information" port:27017 -authentication : MongoDB
5. "Set-Cookie: mongo-express=" "200 OK" : Mongo Express Web GUI
6. "X-Jenkins" "Set-Cookie: JSESSIONID" http.title:"Dashboard" : Jenkins CI
7. "Docker Containers:" port:2375 : Docker APIs
8. "Docker-Distribution-Api-Version: registry" "200 OK" -gitlab : Docker Private Registries 
9. "dnsmasq-pi-hole" "Recursion: enabled" : Pi-hole Open DNS Servers
10. "root@" port:23 -login -password -name -Session : Already Logged-In as root via Telnet
11. "Android Debug Bridge" "Device" port:5555 : Android Root Bridges
12. Lantronix password port:30718 -secured : Lantronix Serial-to-Ethernet Adapter Leaking Telnet Passwords
13. "Citrix Applications:" port:1604 : Citrix Virtual Apps
14. "smart install client active" : Cisco Smart Install
15. PBX "gateway console" -password port:23 : PBX IP Phone Gateways
16. http.title:"- Polycom" "Server: lighttpd" : Polycom Video Conferencing 
17. "Polycom Command Shell" -failed port:23 : Telnet Configuration
18. "Server: Bomgar" "200 OK" : Bomgar Help Desk Portal
19. "Intel(R) Active Management Technology" port:623,664,16992,16993,16994,16995 : Intel Active Management CVE-2017-5689 
20. HP-ILO-4 !"HP-ILO-4/2.53" !"HP-ILO-4/2.54" !"HP-ILO-4/2.55" !"HP-ILO-4/2.60" !"HP-ILO-4/2.61" !"HP-ILO-4/2.62" !"HP-iLO-4/2.70" port:1900 : HP iLO 4 CVE-2017-12542 

**Outlook Web Access**
1. "x-owa-version" "IE=EmulateIE7" "Server: Microsoft-IIS/7.0" : Exchange 2007
2. "x-owa-version" "IE=EmulateIE7" http.favicon.hash:442749392 : Exchange 2010
3. "X-AspNet-Version" http.title:"Outlook" -"x-owa-version" : Exchange 2013 / 2016
4. "X-MS-Server-Fqdn" : Lync / Skype for Business

**Network Attached Storage**
1. "Authentication: disabled" port:445 : SMB (Samba) File Shares
2. "Authentication: disabled" NETLOGON SYSVOL -unix port:445 : Specifically domain controllers
3. "Authentication: disabled" "Shared this folder to access QuickBooks files OverNetwork" -unix port:445 : Concerning default network shares of QuickBooks files
4. "220" "230 Login successful." port:21 : FTP Servers with Anonymous Login
5. "Set-Cookie: iomega=" -"manage/login.html" -http.title:"Log In" : Iomega / LenovoEMC NAS Drives
6. Redirecting sencha port:9000 : Buffalo TeraStation NAS Drives
7. "Server: Logitech Media Server" "200 OK" : Logitech Media Servers
8. "X-Plex-Protocol" "200 OK" port:32400 : Plex Media Servers
9. "CherryPy/5.1.0" "/home" : Tautulli / PlexPy Dashboards

**Webcams**
1. "Server: yawcam" "Mime-Type: text/html" : Yawcams
2. ("webcam 7" OR "webcamXP") http.component:"mootools" -401 : webcamXP/webcam7
3. "Server: IP Webcam Server" "200 OK" : Android IP Webcam Server
4. html:"DVR_H264 ActiveX" : Security DVRs
  
**Printers**
1. "Serial Number:" "Built:" "Server: HP HTTP" : HP Printers
2. ssl:"Xerox Generic Root" : Xerox Copiers/Printers
3. "SERVER: EPSON_Linux UPnP" "200 OK" : Epson Printers
4. "Server: EPSON-HTTP" "200 OK" : Epson Printers
5. "Server: KS_HTTP" "200 OK" : Canon Printers
6. "Server: CANON HTTP Server" : Canon Printers
  
**Home Devices**
1. "Server: AV_Receiver" "HTTP/1.1 406" : Yamaha Stereos
2. "\x08_airplay" port:5353 : Apple TVs, HomePods, etc.
3. "Chromecast:" port:8008 : Chromecasts / Smart TVs
4. "Model: PYNG-HUB" : Crestron Smart Home Controllers
 
**Misc**
1. title:"OctoPrint" -title:"Login" http.favicon.hash:1307375944 : OctoPrint 3D Printer Controllers
2. "ETH - Total speed" : Etherium Miners
3. http.title:"Index of /" http.html:".pem" : Apache Directory Listings
4. http.html:"* The wp-config.php creation script uses this file" : Misconfigured Wordpress 
5. "Minecraft Server" "protocol 340" port:25565 : Minecraft Servers
6. net:175.45.176.0/22,210.52.109.0/24,77.94.35.0/24 : Information related to North Korea
7. port:17 product:"Windows qotd" : Quote of the day protocol
8. "X-Recruiting:" : Finding a Job
  

