# whosopen
This script will help me satisfy my curiosity about how many WAPs are purely open, without any authentication mechanisms whatsoever (not even an agree to AUP prompt). This is a proof of concept script to help map out public wifi spots and should **not** be used for malicious purposes.   

# Using whosopen

whosopen is only avaliable to Linux users, no version for Windows is going to be developed. Your distro must have nmcli and python3 in order for this to work.

To set up and use whosopen, enter the following into the terminal:

1. cd \<replace this with the dir where you downloaded whosopen to\>
2. chmod +x whosopen
3. sudo whosopen \<optional number frequency argument\>

To stop scanning, press CTRL+C repeatedly until it ends.
