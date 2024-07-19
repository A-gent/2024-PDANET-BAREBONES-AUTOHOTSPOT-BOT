# 2024-PDANET-BAREBONES-AUTOHOTSPOT-BOT
For use with PDAnet modem PC connecting to WAN port on routers, OR on any machine without a router by forcing the PC to host a Windows Hotspot using the PDAnet connection, thus using the PC as an all-in-one modem and router.


When AutoConnect=1 in the hotspots.cfg settings file, it will poll for internet connectivity every so often, and if it finds that the internet is not connected, it will attempt to reconnect PDAnet connection.

When AutoHotspot=1 in the hotspots.cfg settings file, it will automatically run the powershell scripts to ensure your Windows Hotspot turns on and stays turned on. It will also automatically close powershell instances that are attempting to remain running in the background.


# SETUP

Place the .ps1 powershell scripts at the root C:\ drive, and enable powershell script execution on your machine.

Run the exe after configuring your hotspots.cfg file.
