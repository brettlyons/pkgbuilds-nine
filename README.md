pkgbuilds-nine
==============

Temporary PKGBUILDs for building Mesa / Wine / Radeon xf86 driver with dx9 state tracker support on Arch Linux.

Mesa/lib32-mesa needs to be built before Wine is built, since wine links to the nine adapter mesa libraries.

-- DEPRECATED -- -- DO NOT USE -- -- NO LONGER NECESSARY -- -- END OF LIFE -- -- SUNSET --

These PKGBUILDs were made several versions of mesa ago.  (10.4ish) and generally version bumped as we went.  As it is now, mesa as availalbe in the Arch [core] repository should fit everyone's needs in this regard (unless you want dev version, in which case mesa-git is availalbe in the AUR), and the Wine package as available in the AUR as wine-staging-d3dadapter.  In other words, it is recommended that you use those, as these pkgbulds will prob. start breaking with version bumps.  As it is, I've removed the PKGBUILDs that were previously hosted here to prevent future collisions with upstream versions.
