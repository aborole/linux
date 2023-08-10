### Enable and disable keyboard as keyboard was not working ###

I installed Linux on my old Lenovo Y510P, and after few days 3rd row of keyboard stopped working. 
I had a spare Logitech Wireless keyboard with me, so was using it, but sometimes, there was a continuous key presses from the laptop keyboard.

I wanted to disable that keyboard, and checked some solutions on Stackoverflow on how to get it of keyboard using "xinput list" and using that can disable/ enable keyboard.
I created a shell script for the same, but it was not consistent.  
After some search, I found a shell script for the same, which was working consistently:
https://github.com/anitaggu/ikbdop/blob/main/ikbdop.sh

I configured it to run that script using keyboard shortcut, but assiging it to "Ctrl+Shift+A" - enable, "Ctrl+Shift+D" - disable

![image](https://github.com/aborole/linux/assets/19694321/3fcfd510-e244-47f3-ba7e-b8b4dd00f000)

