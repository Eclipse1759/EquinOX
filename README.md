# EquinOX
A port of Debian Linux / Raspbian that you can place on an SD card. Because this is a port of Raspbian, It's optimized for computers that use ARM chips. However, I'm working on having it run on all computers. It'll obviously be slower, but... That's also something to work on.

# Goal
I'm trying to have it where you can just copy the contents of the "Core.zip" to the root of the Drive, and select that as your boot up drive. However, Raspbian runs on ARM chips, so I have to re-code the Kernel to have it run on both ARM and Intel. That'll be fun.

Other goals are to:

- Have the OS be able to run .exe's and .app's
- Make sure it uses as small RAM as possible.
- Optimize the GUIs and SMCs for the best user experience possible.
- Unify the Drives so all apps can read the same trail.

# Prerequisites
You will (Preferably) need:

- A Rasberry Pi (Model B)
- An SDHC card with 8 GB minimum
- A Mouse (Not the living one. Those and computers do not work well together.)
- A Github Account
