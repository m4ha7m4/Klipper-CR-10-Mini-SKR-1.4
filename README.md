# klipper-config

Klipper Firmware config for CR-10 Mini with SKR 1.4T board, BTT 3.5" TFT, BL Touch, Filament sensor, 

### Installation

```
cd ~
mkdir  ./klipper_config-$(date +"%Y-%m-%d")/
mv ./klipper_config/* ./klipper_config-$(date +"%Y-%m-%d")/
rm -d -r ./klipper_config/
git clone --recurse-submodules git@github.com:m4ha7m4/klipper_config
```
### Usage

- [Slicer configuration](./macros/README.md)
