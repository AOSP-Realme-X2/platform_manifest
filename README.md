# ANDROID 11 FOR REALME

### Getting started:
To get started with CUSTOM AOSP, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize the CUSTOM AOSP sources locally, use a command like this:
```
$ repo init -u https://github.com/AOSP-Realme-X2/platform_manifest -b android-11
```

Then to sync up:
```
$ repo sync -c -q --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

### Finally, to build: ###
```
$ source build/envsetup.sh
$ lunch aosp_RMX1851-userdebug
$ make otapackage -j$(nproc --all)
```
---------------------------------
Credits:
-----
 * [**ParanoidAndroid**](https://github.com/AOSPA)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**WaveOS**](https://github.com/Wave-Project)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**CypherOS**](https://github.com/CypherOS)
 * [**BenzoRom**](https://github.com/BenzoRom)
 * and the list never ends ...
---------------------------------
