XSSYA is a Cross Site Scripting  Scanner & Vulnerability Confirmation (Woring in two Methods )



* Method number 1 for Confiramtion Request and Response 
* Method number 2 for Confiramtion Execute encoded payload and search for the same payload in web HTML code but decoded
* Suppport HTTPS
* After Confirmation (execute payload to get cookies)
* Identify 3 Types of WAF (Mod_Security - WebKnight - F5 BIG IP)
* Can be run in (Windows - Linux)


XSSYA Countine Library of Encoded Payloads To Bypass WAF (Web Application Firewall)

It Aslo Support Saving The Web Html Code Before Executing the Payload 
Viewing the Web HTML Code into the Screen or Terminal 


$ python xssya.py

Links sould end with (/or=or?)


Example 

$ Pytohn xssya.py

http://www.domain.com/
http://www.domain.com=
http://www.domain.com?

The only Module need to Download is colorama-0.2.7
https://pypi.python.org/pypi/colorama

Note : Crawling (need to be Enhanced)
