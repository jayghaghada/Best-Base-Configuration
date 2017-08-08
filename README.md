# Best-Base-Configuration

![network topology](https://user-images.githubusercontent.com/18054238/29094400-d4efb212-7c52-11e7-9b83-a0029f767aaf.png)

1.Setup hostname to identify router in the network.
2.Use a banner thats legally binding authorized usage of it.
3.Enable "No IP domain-lookup",so that every time you misstype something,yoou don't have to wait for 30 seconds or so.
4.Enable logging synchronous
5.Enable console line password to prevent unathorized access to anyone who has physical access to device.
6.Enable VTY line password for telnet access to router.
7.Enable "service password-encryption"
8.Enable "Enable secret"
9.Assign IP address to interface.
10.Lastly,copy the running configuration to startup configuration.

USAGE: PASSWORDS
all passwords are "cisco"
