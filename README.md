# CVE_2016-10033
Exploiting PHPMail with back connection (reverse shell) from the target

https://www.exploit-db.com/exploits/40974/

Usage:

    1 - Download docker vulnerable enviroment at: https://github.com/opsxcq/exploit-CVE-2016-10033
    2 - Config your IP for reverse shell on payload variable
    4 - Open nc listener in one terminal: $ nc -lnvp <your ip>
    3 - Open other terminal and run the exploit: python3 anarcoder.py
 
Video PoC:

    https://www.youtube.com/watch?v=DXeZxKr-qsU
 
Full Advisory:

    https://legalhackers.com/advisories/PHPMailer-Exploit-Remote-Code-Exec-CVE-2016-10033-Vuln.html
