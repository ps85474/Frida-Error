# Resolve Frida Errors with version 16.*

Use this link to download frida server https://github.com/frida/frida/releases/download/16.0.8/frida-server-16.0.8-android-x86_64.xz

Extract this frida file and push to android device.

use below commands to run frida server:
>adb shell
>su
>cd /data/local/tmp
>chmod +x frida-*
>./frida-server-* &


# Resolve Objection/Frida gadget error (Windows/Linux):

Use this link to download frida gadget https://github.com/frida/frida/releases/download/16.0.8/frida-gadget-16.0.8-android-arm64.so.xz

Extract the file and rename to gadget-android-arm64.so

Linux:
Go to home directory and nevigate to .cache folder and create a new folder with name "frida" and paste the "gadget-android-arm64.so" file there and reboot the system.


Windows:
Login with administrator and navigate to C:\Users\Roy\AppData\Local\Microsoft\Windows\INetCache> and create folder with name "frida" and paste the "gadget-android-arm64.so" file there and restart the system.


Note: if it's not work, run frida server as root in Android.


Happy Hunting!!
