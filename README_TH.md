![1000000187](https://github.com/Hanakohiraki/custom_twrp_samsung_a05s/assets/123821106/11f89f1d-1203-4c17-9687-dc7213652e35)

Upcoming languages: [Thai](http://simp.ly/p/j11rGV)/[Indonesian](http://simp.ly/p/j11rGV)/[English](http://simp.ly/p/j11rGV)

# Android device tree for samsung SM-A057F (A05s)

>  TWRP อาจจะนังไพร้อมใช้งานตอนนี้ โปรดติดตั้งด้วยความระมระวัง
> 
>  โปรดอ่านอีกครั้ง "TEST" แปลว่า กำลังทดสอบ

# Clone Tree
    git clone https://github.com/TheNoobDevs/custom_twrp_samsung_a05s -b twrp-12.1 device/samsung/a05s
    
# Build twrp
    ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_a05s-eng; mka recoveryimage

# WARNING!!!!!!
หากคุณ UNLOCKING BOOTLOADER อุปกรณ์ของคุณจะทำการรีเซ็ตตัวเอง
> เราขอแนะนำให้คุณ "รูท" อุปกรณ์ของคุณเพื่อคัดลอกข้อมูลการกู้คืน TWRP ที่ผิดพลาด  คุณสามารถส่งสิ่งนี้ให้นักพัฒนาซอฟต์แวร์เพื่อแก้ไขปัญหานี้ได้
 >
 > สำหรับตอนนี้ เราขอแนะนำให้อดทนรอเวอร์ชันเบต้าอย่างเป็นทางการจากนักพัฒนา
 >
 > หากคุณต้องการติดตั้งจริงๆ โปรดใช้ [เวอร์ชันล่าสุด](https://github.com/TheNoobDevs/custom_twrp_samsung_a05s/releases)

# install (Not recommended at this time)
 Samsung has a system that prevents you from uninstalling TWRP manually when you boot into TWRP. It might be annoying, but you have to wait for the next update to prevent it from automatically uninstalling.

 # UNLOCK BOOTLOADER
 If you have not UNLOCK BOOTLOADER yet, please UNLOCK BOOTLOADER before installing TWRP.

 If you have already installed  Follow this step.

 # Install (UNLOCK BOOTLOADER)
 1. Turn off your phone.
 2. Plug the USB into your computer and phone.
 3. Press all the buttons you see (Volume Down + Volume Up + Power Button).

 > Your device will reset or wipe your phone completely.
 >
 > Please be careful if you do not want to reset your data.  We do not provide a way to UNLOCK BOOTLOADER without resetting your phone.
 >
 > Even if it's a bit "annoying"

 4. If there is a blue screen with 3 options, press and hold the volume up button (UNLOCK BOOTLOADER).
 5. Then OK, then wait~~
 6. Success!!

 # Install (Enter download mode)
 1. Turn off your phone.
 2. Plug the USB into your computer and phone.
 3. Press all the buttons you see (Volume Down + Volume Up + Power Button).
 4. Press the volume up button, then you will be in download mode.
 5. Plug the USB into your computer and phone, then go to your computer.
 6. Open ODIN, upload recovery file into AP. 
 7. Set not to reboot automatically.
 8. Start!
 9. If your ODIN says PASS!  That means it's successful!!!
 10. Press volume down + power button 7-10 seconds.

 # How to enter??

 1. Turn off your phone.
 2. Plug the USB into your computer and phone.
 3. Press the volume up button + power button.
 4. Failed to pass UNLOCK BOOTLOADER warning.
 5. Wait
 6. You can now enter!!
 7. 
