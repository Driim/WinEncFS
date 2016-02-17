# WinEncFS - Windows port of EncFS 

## About

EncFS4win is a revival of the original encfs4win project, but has been brought 
up-to-date with recent changes done to the EncFS project.  The original encfs4win 
was based on EncFS v1.7.4, which was shown to have some [security issues](https://defuse.ca/audits/encfs.htm). 
[Updates to EncFS](https://github.com/vgough/encfs) have been done recently to fix many of these issues, and the goal of 
this project is to port these modernizations to Windows. 

EncFS provides an encrypted filesystem in user-space. It runs in userspace,
using the [Dokan library](https://github.com/dokan-dev/dokany) for the filesystem interface. EncFS is open source
software, licensed under the LGPL.

EncFS encrypts individual files, by translating all requests for the virtual
EncFS filesystem into the equivalent encrypted operations on the raw
filesystem.

For more info, see:

 - The excellent [encfs manpage](encfs/encfs.pod)
 - The technical overview in [DESIGN.md](DESIGN.md)


## Credits

Special thanks to [vgough/encfs](https://github.com/vgough/encfs),[freddy77/encfs4win](https://github.com/freddy77/encfs4win) and [jetwhiz/encfs4win](https://github.com/jetwhiz/encfs4win)
for establishing the groundwork that made this project possible! 
