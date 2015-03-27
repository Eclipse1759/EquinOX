# EquinOX
A port of Debian Linux / Raspbian that you can place on an SD card. I'm trying to have it run on Rasberry Pi, but that's still questionable with all of the edits that are to be made.

# Goal
I'm trying to have it where you can just copy the contents of the "Core.zip" to the root of the SD card, and select that as your boot up drive. However, Raspbian runs on ARM chips, so I have to re-code the Kernel to have it run on both ARM and Intel. That'll be fun.

Other goals are to:

- Have the OS be able to run .exe's and .app's
- Make sure it uses as small RAM as possible.
- Optimize the GUIs and SMCs for the best user experience possible.
- Unify the Drives so all apps can read the same trail.

