The Android Open Source Project Lollipop 5.0
===========

To initialize your local repository using the AOSP trees, use a command like this:

    repo init -u git://github.com/redmi1s-aosp/manifest.git -b aosp-5.0

Then to sync up:

    repo sync

Finally to build:

    . build/envsetup.sh
    lunch aosp_armani-userdebug
    make bacon -j#

 #=PC core number+thread number


*Special thanks to F-AOSP (Alberto97) and armani-dev (Kra1o5, fefifofum)
