# PianoFromAbove Colorloop

### Features:  
• Realtime track color switching  
• 16 color track changes directly onto PFA, with rainbow preset  
• Ability to load config.xml in realtime  

Contains strictly only changes to GUI and color track handling. Built with VS2010

## How to build

* clone this repo
* Download and install VisualStudio 2010
* Download and install Direct X SDK
* Download and extract Google Protocol Buffers 2.5
  * Build libprotobuf-lite.vcproj
* Download and extract Boost 1.55
* Open the .sln and edit the VC++ Directories from the project properties so that the Include Directories and Library Directories point to the location of your boost and protocol buffers downloads
* Cross fingers
* Build! (Release, x64)

Once that's done, there should be a Release\PFA-1.1.0-x86_64.exe that you can run.

There's an optional .nsi script that you can run if you want to build an installer.
