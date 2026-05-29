# Device Tree for Xiaomi Redmi Note 9 (merlin)

This is the device tree for compiling **TWRP Recovery** for the Xiaomi Redmi Note 9 (codename: **merlin**).

## Device Specifications

| Feature | Details |
| :--- | :--- |
| Device | Redmi Note 9 |
| Codename | merlin |
| SoC | MediaTek Helio G85 |
| Base ROM | MIUI V13.0.2.0.SJOMIXM (Android 12) |

## Build Requirements
1. **Environment**: Ubuntu 20.04/22.04 or later (or WSL2 on Windows).
2. **Tools**: Installed `repo` and Android build tools.
3. **Source**: Use the OmniROM source tree (which TWRP is based on).

## Compilation Steps
1. Initialize the build environment:
```bash
   repo init -u [https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git) -b twrp-12.1
   repo sync
