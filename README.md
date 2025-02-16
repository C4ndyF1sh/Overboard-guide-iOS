# How to use Overboard

1. First get Bootstrap:https://github.com/roothide/Bootstrap/releases and install it then click the boostrap button. 

2. Then go to Sileo and search for OpenSSH install it.

3. After go to Boostrap and enable OpenSSH and Tweak Enable.

4. Then go to App List and enable the app you want to override the memory usage of.

5. After that go back to Sileo and install Roothide Patcher. 

6. Then download this: https://github.com/stossy11/Overboard-guide/raw/refs/heads/main/Build%20Output.zip and import the .deb file of your need into Roothide Patcher.

7. When its finsihed click on the Sileo button, click get and that will install the .deb file.

8. Then SSH into your iPhone with terminal using ssh mobile@_YouriPhoneIPhere_

After open the app you want to use the tool on i will use*:

**Here is the command:**


8GB devices: jetsamctl -l 7490 Pomelo

6GB devices: jetsamctl -l 5490 Pomelo

4GB devices: jetsamctl -l 3490 Pomelo

3GB devices: jetsamctl -l 2490 Pomelo


*On iOS 16+ you need to use this command, Replace 5490 with the ones recommened above for your device ram:*
`while true; do jetsamctl -l 5490 MeloNX; sleep 1; done`



