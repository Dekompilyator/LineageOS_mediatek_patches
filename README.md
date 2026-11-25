# LineageOS 14.1 Common Patches for MediaTek MT67xx Devices

Common patches for LineageOS 14.1 (Android 7.1.2) on legacy MediaTek MT67xx devices.

## Usage

1. Clone the repository into your device tree's patches directory:
   ```bash
   git clone -b los-14.1 https://github.com/Dekompilyator/LineageOS_mediatek_patches.git /lineage-source-dir/device/manufacturer/codename/patches
   ```

2. Update any path or repository variables in the scripts to match your device and build tree layout.

3. Apply the patches from the root of your LineageOS source tree:
   ```bash
   source device/manufacturer/codename/patches/apply-patches.sh
   ```

4. Reverse the patches if needed:
   ```bash
   source device/manufacturer/codename/patches/revert-patches.sh
   ```

## Credits

* LineageOS Team
* darklord4822
* Everyone else who contributed commits and fixes
