# How to get log of mirror4cast #
  * when you meet problem for mirror4cast, e.g.: could not start mirror service, please provide log to google group: http://groups.google.com/group/mirror4cast

# the information you need to provide for your android device #
  * version of android
  * brand name
  * model number
  * ROM name if you have a special ROM

# windows #
  * 1. install adb tool
    * http://forum.xda-developers.com/showthread.php?t=2317790
      * install adb tool from above link
  * 2. get log of your android device
    * then run adb tool on your windows:
      * e.g.:
        * C:\Program Files\Minimal ADB and Fastboot>adb logcat -v threadtime > d:\mirror4cast.log
        * please change "d:\mirror4cast.log" to a folder you want.
    * run mirror4cast
    * reproduce the issue
  * 3. send log to google group
    * http://groups.google.com/group/mirror4cast
    * send the mirror4cast.log to above group
# linux #
  * 1. install adb tool
    * sudo apt-get install android-tools-adb
  * 2. get log of your android device
    * on your linux PC:
      * adb logcat -v threadtime | tee ~/mirror4cast.log
    * start mirror4cast
    * reproduce the issue
  * 3. send log to google group
    * group: http://groups.google.com/group/mirror4cast
    * please send ~/mirror4cast.log to this group