# whosopen
Script that allows you to scan for unauthenticated public wifi hotspots and get their IP address. This is a proof of concept script written to help map out public wifi spots and should ***not*** be used for malicious purposes. It was written out of boredom and curiosity.  

# Using whosopen

whosopen only works with Linux systems, no version for Windows is currently being worked on. Your distro must have nmcli, ping, and python3 in order for this to work (basically every distro should have this).

To set up and use whosopen, enter the following into the terminal:

1. cd \<replace this with the dir where you downloaded whosopen to\>
2. chmod +x ./whosopen
3. sudo ./whosopen \<optional number frequency argument\>

To stop scanning, press CTRL+C repeatedly until it ends.

# Hopes and Dreams

Maybe in the future I'll include some kind of function to map IP addesses to approximate coordinates (script assumes you don't have GPS) in order to make a pretty map for social media sharing or personal knowledge (good to know where you can get that sweet sweet, modern life enabling, wifi), n stuff. Btw, if you want to use this to map out public wifi for personal use, please use a VPN with it. Public wifi be nasty: you don't know if the hotspot you're connecting to is malicious and sniffing all your packets.

# Notes

If you want to use this to make a map of open hotspots, do it quickly after data collection. IP addresses are dynammically allocated by ISPs, so your data will expire quickly.
