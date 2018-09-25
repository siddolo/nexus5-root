# Nexus 5 Root

## Unlock Bootlader, Custom Recovery, Root

```
## Unlock bootloader (all data will be lost)
fastboot oem unlock

## Flash recovery
fastboot flash recovery twrp-3.1.0-0-hammerhead.img

## Root
adb push SR5-SuperSU-v2.82-SR5-20171001224502.zip /sdcard/
- From Recovery: Install -> choose zip
```


## Fix bootloop after installing custom recovery

- Reinstall stock recovery
- Start normally


## Factory Images

https://developers.google.com/android/images#hammerhead


## References

https://forum.xda-developers.com/google-nexus-5/general/guide-nexus-5-how-to-unlock-bootloader-t2507905

https://forum.xda-developers.com/google-nexus-5/general/index-google-nexus-5-roms-kernels-mods-t2475401
