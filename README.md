# TWRP tree for CMDC M636 (M636)

To build TWRP:
--------------

repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-5.1

repo sync -j8

. build/envsetup.sh

lunch omni-M636-userdebug

make recoveryimage -j8

