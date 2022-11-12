# Pixel Inside #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/Pixel-Inside-13/manifest -b thirteen-plus

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

### Credits ###

* [**Pixel Experience**](https://github.com/PixelExperience/)
* [**Syberia Project**](https://github.com/syberia-project/)
* [**VoidUI**](https://github.com/VoidUI-Tiramisu/)
* [**ArrowOS**](https://github.com/ArrowOS/)
