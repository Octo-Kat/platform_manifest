AOSP 4.4 KitKat for Galaxy S4
=============================



Download:
----------
* mkdir ~/AOSP
* cd ~/AOSP
* repo init -u git://github.com/Octo-Kat/platform_manifest -b kk-4.4
* repo sync


Building:
----------
* . build/envsetup.sh
* lunch
* make otapackage
