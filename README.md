Stank_Cheese_N8013
==================

GT-N8013_JB OpenSource Stank Cheese Kernel - https://github.com/PoonKang/Kernel_GT-N8013_JB.git

Installing on a root injected device without increasing binary count.

# Push to sdcard
adb push boot.img /sdcard/boot.img

# Flash the boot
adb shell

cd sdcard

su

dd if=boot.img of=/dev/block/mmcblk0p5 bs=1024

adb reboot

May also tar and flash in PDA section of Odin! Enjoy!
