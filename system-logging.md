# Version ‼️
After reviewing _that sounds bad_ information events, and repeated warnings in windows event viewer on various systems, and after further review of KB articles and fixes and reports of troublehooting, I'm starting to wonder if it's posible to have a clean system.  
If it is, it's going to be pretty hard trying to keep it clean... or is it?

## Logging Setup - Install
Windows Build Type - "image version" [Version 10.0.22631.3085]
Windows DISM setup - installed/removed components
Hardware Install - Device Components, device driver storage
Registry Tweaks - Config options, in addition to OOBE config... all adds up!

HP SmartAudio (control panel) not working - remove? remove other assemblies for other architectures?
- 🐛 On Windows 11 Clean (after windows updates on wifi connect) issues with conexant media installs stuck/failing,
+ brightness keys don't work when cx services stopped to suppress annoying popup conexant factory error

  Other things to check

  GRUB - why two instances of disk 1 in uefi boot menu
  why different boot icons when both vhd? **bcdboot**ing

  - check logs
something may have failed, causing knock-on issues. Try to nip in bud
  - backup
Main "lab" workstation is fast, but could be riddled. Lots of weirdness. Configure! Analyse! Unit Test!
  - automate!
Event Viewer + Task Scheduler have some great features, but when enough information is present, PowerShell will help diff across systems, and yield comparisons between configs and "system snapshots"

