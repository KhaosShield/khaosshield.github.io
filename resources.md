---
layout: page
title:  Resources
---

# [](#header-1)>nano Resources

A list of resources i have gathered throughout my journey listed here for easy reference. I have tried to give credit where i can however if anything is missing
or is wrong please let me know, Alot of these have come from my notes pasted into Cherry Tree and ive long since lost the original page..

(In no particular order yet!)


* * *
### [](#header-3)>OSCP Study Guides/Blogs 

Other peoples experinces and study guides / best practices that aided them through the OSCP. Full of great advice and guidance to give you a steer in the right direction.  

[TJNull OSCP Study Guide](https://www.netsecfocus.com/oscp/2019/03/29/The_Journey_to_Try_Harder-_TJNulls_Preparation_Guide_for_PWK_OSCP.html) Probably the best resource & advice i have come across so far in my journey.
[thomfree.dev](https://thomfre.dev/my-oscp-experience) Advice, tools, setups. Current and relevant, Fantastic blog.  
[HakLukes Ultimate OSCP Guide Pt 1](https://medium.com/@hakluke/haklukes-ultimate-oscp-guide-part-1-is-oscp-for-you-b57cbcce7440) 1/3 - Intro & Questions   
[HakLukes Ultimate OSCP Guide Pt 2](https://medium.com/@hakluke/haklukes-ultimate-oscp-guide-part-2-workflow-and-documentation-tips-9dd335204a48) 2/3 - Workflow & Docs  
[HakLukes Ultimate OSCP Guide Pt 3](https://medium.com/@hakluke/haklukes-ultimate-oscp-guide-part-3-practical-hacking-tips-and-tricks-c38486f5fc97) 3/3 Practical tips & tricks  
[oxDarkVortex](https://0xdarkvortex.dev/index.php/2018/04/17/31-days-of-oscp-experience/) 31 Days of OSCP Experience  

Its worth noting that the majority of the links posted here will be for the previous iteration of the OSCP (before the 2020 update) and as such some things will have changed and may be outdated however the great advice and tips are immortal.    

* * *  
### [](#header-3)>HackTheBox & VulnHub OSCP 
If you read TJNull's OSCP study guide above (Which you should have) then you will see he has created a fantastic resource of OSCP like machines available on both HackTheBox & VulnHub. As im currently subscribed to HTB VIP in order to access the "Retired" machines ive extracted the following image to here for a quick reference. Ill flesh this out as we go on and post writeups in the relevant section as i make my way through each box.

![](https://github.com/KhaosShield/khaosshield.github.io/blob/master/assets/2020-04-06%2013_11_09-NetSecFocus%20Trophy%20Room%20-%20Google%20Sheets.png?raw=true)

* * *
### [](#header-3)>Cheatsheets
[XSS Payloads](https://github.com/Pgaijin66/XSS-Payloads/blob/master/payload.txt) (Top 20 are the standard 'go-to' to try first)  
[PHP Reverse Web Shell](http://pentestmonkey.net/tools/web-shells/php-reverse-shell) (A good collection of resources too!)  
[HighOn.Coffee](https://highon.coffee/blog/reverse-shell-cheat-sheet/#kali-php-web-shells) (An awesome site for shells, cheatsheets & everything else)  

* * * 


Upgrading shit shells:~
> -c 'import pty;pty.spawn("/bin/bash")'  
            echo os.system('/bin/bash')  
            /bin/sh -i  
            awk 'BEGIN {system("/bin/sh")}'  
            find / -name blahblah 'exec /bin/awk 'BEGIN {system("/bin/sh")}' \;  
            python: exit_code = os.system('/bin/sh') output = os.popen('/bin/sh').read()  
            perl -e 'exec "/bin/sh";'  
            perl: exec "/bin/sh";  
            ruby: exec "/bin/sh"  
            lua: os.execute('/bin/sh')  
            irb(main:001:0> exec "/bin/sh"  
>

* * *

