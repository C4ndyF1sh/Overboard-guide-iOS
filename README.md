# How to use Overboard
//////////////
**Bootstrap-Method** (iOS 14.0 - 16.7RC/17.0b1 - 17.0):
1. First get Bootstrap:https://github.com/roothide/Bootstrap/releases and install it then click the boostrap button.
2. Then go to Sileo and search for OpenSSH install it.
3. After go to Boostrap and enable OpenSSH and Tweak Enable.
4. Then go to App List and enable the app you want to override the memory usage of.

5. After that go back to Sileo and install Roothide Patcher. 

6. Then download this: https://github.com/stossy11/Overboard-guide/raw/refs/heads/main/Build%20Output.zip and import the .deb file of your need into Roothide Patcher.

7. When its finsihed click on the Sileo button, click get and that will install the .deb file.

8. Then SSH into your iPhone with terminal using ssh mobile@_YouriPhoneIPhere_

9. Enter the command in the Terminal (scroll down)


//////////////////////
**Dopamine-Method** (iOS 15.0 - 16.5(.1)):

1. First get Dopamine (https://github.com/opa334/Dopamine) and jailbreak through it
2. Then go to Sileo and search for OpenSSH install it.
3. Then download this: https://github.com/stossy11/Overboard-guide/raw/refs/heads/main/Build%20Output.zip and import the .deb file into Sileo.
4. Install a Terminal through Sileo (NewTerm3 Beta for example)
5. Enter the command in the Terminal (scroll down)
////////////////////////////////////////////////////




**Maximum recommended value for each device**:

8GB devices: 7490

6GB devices: 5490

4GB devices: 3490

3GB devices: 2490

------------------------------------------
**(iOS 14 - 15) (Replace 5490 with the ones recommened above for your device ram):
**
jetsamctl -l 5490 *App Name*

-------------------------------------------

**On iOS 16+ you need to use this command, Replace 5490 with the ones recommened above for your device ram:
**
while true; do jetsamctl -l 5490 *App Name*; sleep 1; done

**If this doesn´t work, try enabling swap instead (Replace 5490 with the ones recommened above for your device ram)**
while true; do jetsamctl -l 5490 -M 5490 *App Name*; sleep 1; done


