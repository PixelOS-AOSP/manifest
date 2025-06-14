# NothingExperience

## Getting Started

To get started with the NothingExperience sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
repo init -u https://github.com/NothingExperience/manifest.git -b fifteen --git-lfs
```

Then sync up:

```bash
repo sync
```

## Building the System

Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch aosp_devicecodename-target_release-buildtype
```

Start compilation

```bash
mka bacon
```

---

Note:  

**target_release**: bp1a (As of April ASB)  
**buildtype**: user, userdebug, eng

