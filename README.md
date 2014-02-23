TitanOS_manifest
================

HOW to build TitanOS


repo init -u git://github.com/Mungohigh/manifest.git -b master

then repo sync

then . build/envsetup.sh

then lunch

then pick your device

then make otapackage -j<number of jobs> 
