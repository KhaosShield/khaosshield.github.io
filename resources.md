---
layout: page
title:  Resources
---

# [](#header-1)>nano Resources

A list of resources i have gathered throughout my journey listed here for easy reference. I have tried to give credit where i can however if anything is missing
or is wrong please let me know, Allot of these have come from my notes pasted into Cherry Tree and ive long since lost the original page..

(In no particular order yet!)


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

