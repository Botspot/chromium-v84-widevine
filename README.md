# chromium-v84-widevine
## Widevine DRM for `chromium-browser` v84.
[![badge](https://github.com/Botspot/pi-apps/blob/master/icons/badge.png?raw=true)](https://github.com/Botspot/pi-apps)  
This was adapted from the version of `widevine-flash_armhf.sh` that can be obtained from [here](https://gist.github.com/ruario/19a28d98d29d34ec9b184c42e5f8bf29#file-widevine-flash_armhf-sh).  
This **chromium-v84-widevine** does not download a 2GB ChromeOS image file, but simply downloads the two files you need: `/opt/WidevineCdm/_platform_specific/linux_arm/libwidevinecdm.so` and `/opt/WidevineCdm/manifest.json`.  

## To install: 
```
git clone https://github.com/Botspot/chromium-v84-widevine
sudo cp -a ~/chromium-v84-widevine/WidevineCdm /opt
```
## To uninstall:
```
sudo rm -r /opt/WidevineCdm
```
