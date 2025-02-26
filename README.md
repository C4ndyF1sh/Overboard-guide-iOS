# Bootstrap-Method
(supports up to 16.7RC/17.0b1-17.0)
1. Get Bootstrap https://github.com/roothide/Bootstrap and install it via TrollStore https://ios.cfw.guide/installing-trollstore
2. Go to Bootstraps settings and enable Tweak Enable.
3. Go to App List and enable app injection for MeloNX
4. Go back to Sileo/Zebra and install Roothide Patcher.
5. Then download this: https://github.com/stossy11/Overboard-guide/raw/refs/heads/main/Build%20Output.zip and import the .deb file of your need into Roothide Patcher.
6. When its finished click on the Sileo/Zebra button, click get and then wait till it’s installed
7. Execute command (see below)

# Dopamine/Nathanlr-Method
(Dopamine supports up to 16.5(.1), while Nathanlr supports 16.5.1 - 16.6.1)

1. Get **Dopamine** (https://ios.cfw.guide/installing-dopamine/) Or **Nathanlr** (https://ios.cfw.guide/installing-nathanlr/)

2. **Download** this: https://github.com/stossy11/Overboard-guide/raw/refs/heads/main/Build%20Output.zip and import the iPhoneOS arm.deb file into Sileo/Zebra

3. **Execute the command**

# Executing the Command(s)

**Terminal Method** (Make sure MeloNX is open in the background)
1. Install NewTerm3 Beta from Sileo/Zebra
2. Execute "while true; do jetsamctl -l 5490 -M 5490 App Name; sleep 1; done" in NewTerm3 Beta

**Note**: Replace value "5490" with the amount of ram you need in total (ram+physical storage) in mb, so 5.5gb = 5500 for example

**Control Center Module Method (Dopamine/Nathanlr-only)** (Make sure MeloNX is open in the background)
1. Download this .zip file and extract it https://github.com/C4ndyF1sh/Overboard-guide-iOS/releases/tag/requirements
2. Share the .deb file with Sileo/Zebra and install it
3. Open Settings > Control Center > add "CommandModule"
4. Open Filza
5. Replace the **com.captinc.commandmodule.sh** file at "**/var/jb/var/mobile/Library/Preferences**"
6. Tap on the new added Control Center Module **once**

**Note**:  When tapping more than once per boot on the cc module it may reduce performance, if you did this accidently or not you can just respring through TrollStore or a other app and tap on the cc module once again after.
