# xall
This is a forensic data and file extractor from devices and image files. sudo ./xall_1.5.sh for running it. It mounts a DD/EWF image files or devices (e.g. /dev/sdb); it extracts all the allocated files, it extracts all deleted files and the slack space; It makes a data carving on the free space only. You can choose each type of extraction. It uses a GUI made with YAD (Yet Another Dialog), so it's simple and fast to use.
You need:
Don't use blank spaces in the image filename!
YAD
XMount
The Sleuthkit (latest release)
Photorec
MD5Deep
