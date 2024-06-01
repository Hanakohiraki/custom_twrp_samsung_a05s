# Android device tree for samsung SM-A057F (a05s)

# Clone Tree
    git clone https://github.com/TheNoobDevs/custom_twrp_samsung_a05s -b A14 device/samsung/a05s
# Build twrp
    ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_a05s-eng; mka recoveryimage

# WARNING!!!
UNLOCKING YOUR BOOTLOADER WILL VOID YOUR WARRENTY!
