![1000000187](https://github.com/Hanakohiraki/custom_twrp_samsung_a05s/assets/123821106/11f89f1d-1203-4c17-9687-dc7213652e35)

# Android device tree for samsung SM-A057F (A05s)

>  TWRP may not be complete yet. Please install with care.
> 
>  Please read again "TEST" so there may be an error

## Clone Tree
    git clone https://github.com/TheNoobDevs/custom_twrp_samsung_a05s -b twrp-12.1 device/samsung/a05s
    
## Build twrp
    ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_a05s-eng; mka recoveryimage

# WARNING!!!!!!
If you UNLOCKING BOOTLOADER in your phone Your device may Die/Void/Warranty expired/Lost your friend. Please be careful when UNLOCKING BOOTLOADER on your device.

> [NOTE]
> 
> We recommend that you "root" your device to copy your faulty TWRP recovery data. You can send this to the developer to fix this.
>
> For now, we recommend patiently waiting for the official BETA version from the developers.
> 
> If you really want to install Please use the [latest version](https://github.com/TheNoobDevs/custom_twrp_samsung_a05s/releases)
