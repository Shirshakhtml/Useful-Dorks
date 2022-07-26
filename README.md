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
  
  
  
  
  
  
