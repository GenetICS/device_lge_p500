android_device_lge_p500
==========================

Device configuration for LGE Optimus One LGE-P500

Getting Started
---------------

To get started with Android for ARMv6/CyanogenMod, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/version-control.html).

To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u git://github.com/GenetICS/manifest.git -b ics

Then to sync up:

    repo sync
    sh vendor/cm/get-prebuilts

Then apply patches:

    sh device/lge/p500/patches/install.sh
    sh device/lge/p500/patches/uninstall.sh

Build your device:

    source build/envsetup.sh
    brunch p500

Flash ZIP:

    out/target/product/p500/cm-VERSION-DEVICENAME.zip


Please see the [CyanogenMod Wiki](http://wiki.cyanogenmod.org/) for building instructions.

For more information on this Github Organization and how it is structured,
please [read the wiki article](http://wiki.cyanogenmod.org/index.php/Github_Organization)

Disclaimer
--------

All of these device are not supported by CyanogenMod since they use the old Qualcomm
Snapdragon MSM7x27 chip, and hence cut off by the CyanogenMod team. This team (GenetICS)
is in no way, shape or form affiliated by the CyanogenMod team and this project is not
endorsed or supported by the CyanogenMod team.


