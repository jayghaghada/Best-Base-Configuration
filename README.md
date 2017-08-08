# Best-Base-Configuration

![network topology](https://user-images.githubusercontent.com/18054238/29094400-d4efb212-7c52-11e7-9b83-a0029f767aaf.png)

![banner](https://user-images.githubusercontent.com/18054238/29095277-e2b1fd76-7c55-11e7-80b2-f9c2747c080d.png)

<b>These are the 10 base steps for any router to be configured:</b><br><br>
1.Setup hostname to identify router in the network.<br>
2.Use a banner thats legally binding authorized usage of it.<br>
3.Enable "No IP domain-lookup",so that every time you misstype something,yoou don't have to wait for 30 seconds or so.<br>
4.Enable logging synchronous.<br>
5.Enable console line password to prevent unathorized access to anyone who has physical access to device.<br>
6.Enable VTY line password for telnet access to router.<br>
7.Enable "service password-encryption".<br>
8.Enable "Enable secret".<br>
9.Assign IP address to interface.<br>
10.Lastly,copy the running configuration to startup configuration.<br>

USAGE: PASSWORDS<br>
All passwords are "cisco"
