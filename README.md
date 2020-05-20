## MapleStory Global v179.4 Localhost Enabler + Remote Server

- NGS Removed
- MSCRC Patched
- Nexon Logging Removed
- Multi Client Enabled

Launched via the following...

    MapleStory.exe GameLaunching 8.31.99.141 8484

## Compile Instructions:

- Use Visual Studio 2017/2019 and allow to update to latest (if asked)
- For Local use: Build Solution as // and place in maplestory folder
- For a remote/hosted server, replace the following string in Global.h :

    #define OPT_APPNAME			"Rebirth 176"

    #define OPT_APPVERSION		"3.2"

    #define OPT_ADDR_HOSTNAME	"127.0.0.1"
    
  With your own servers name, version (usually an internal version, like 1.0), and your hosted server IP
  and Build Solution for D 32?? and place in maplestory folder, along with example .bat script. Run the Start.bat to profit!
