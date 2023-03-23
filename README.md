# rz-bsp

Yet another Renesas RZ BSP environment (experimental)

## Instructions

Clone this repo with the below command.

    git clone --recursive https://github.com/renesas-rz/rz-bsp

Configure and build as the below.

    cd rz-bsp
    rzg2_bsp_scripts/yocto_setup/setup.sh
    source poky/oe-init-build-env
    bitbake core-image-bsp

