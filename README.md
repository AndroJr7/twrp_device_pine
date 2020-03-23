# twrp_device_pine
Codename: pine


---------------------------------
TWRP Recovery tree for pine 
---------------------------------

*To build*-

1) Sync Sources 

``$ git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0``

``$ repo sync``


2) Build process

``$ cd SOURCE_DIR``

``$ git clone https://github.com/AndroJr7/twrp_device_pine.git -b twrp-classic device/xiaomi/pine``

``$ git clone https://github.com/AndroJr7/kernel_xiaomi_sdm439 -b twrp kernel/xiaomi/pine``

``$ . build/env*``

``$ lunch omni_pine-eng``

``$ mka recoveryimage``


That's all ! Enjoy...
