# My OSDCloud scripts

## ⚙️ Starter-OSDCloud.ps1
Example: 

**.\Starter-OSDCloud.ps1 -ADK -New -Workspace C:\OSDCloud -WebPSScriptWs1 -Wallpaper C:\Tmp\myWallpaper.jpg -BuildISO**
- Download and install ADK and WinPe Addon (version 10.1.22000.1)
- Install module OSD (-new = force module installation) 
- Create a new OSDCloud Workspace to C:\OSDCloud 
- Inject my custom WebPSScript (https://raw.githubusercontent.com/maehjr12/OSDCloud/main/ws1-OSDCloud.ps1)
- Set the Services Wallpaper
- Build ISOs (one with prompt, one without prompt)
