# PixelOS #

### Initialize local repository ###
```
repo init -u https://github.com/PixelOS-Pixelish/manifest -b staging/twelve
```

### Sync ###
```
repo sync --force-sync
```

### Build ###

```
$ . build/envsetup.sh
$ lunch aosp_$device-user
$ mka bacon -j$(nproc --all)
```
