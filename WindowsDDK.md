The Windows DDK contains the HID library necessary for building a project with the wiimote-api. MinGW already includes the necessary files (in the win32-api). If you're using something like MSVC, you'll probably need the Windows DDK.

It's found [here](http://www.microsoft.com/whdc/devtools/ddk/default.mspx) @ 236 MB last time I checked.

At least one [website](http://www.alanmacek.com/usb/#Example_Host_Code) offers the specific files needed, however, I'm unsure of what the licensing issues are with redistributing those files which is why I have not posted them here.

