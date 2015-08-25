##Android USB Device Mounter

Copyright 2015 eosrei

Mounts two (or more?) USB devices at the same time allowing data to be
moved between devices.

There may be more elegant ways to do this, but it works and that's better
than anything I can find on the Internet. This is currently just a shell
script which locates all available devices located at /dev/block/ and
attempts to mount them under directories at /sdcard/mnt/.

Usage:

1. Copy mbtusb to /sdcard
2. Start Terminal
3. `su` to root
4. `cd /sdcard`
5. `sh mntusb` Look for any errors, it's as verbose as possible.
6. Start your file manager
    

*This works on my phone. I cannot say if it will work on yours. This may
just end up being notes to myself.*
