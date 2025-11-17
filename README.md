# i.MX25 Build Manifest

This manifest sets up the complete build environment for i.MX25 PDK.

## Quick Start
```bash
mkdir imx25-project
cd imx25-project
repo init -u https://github.com/pujan3008/imx25-build-manifest.git
repo sync
```

## What Gets Downloaded

- Poky (Yocto base)
- meta-freescale
- meta-freescale-distro  
- meta-openembedded
- meta-ei-imx25 (custom layer)
