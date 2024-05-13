You will also like to see https://github.com/lgs2007m/cdt-gpt-ipq60xx-generate

U-Boot source code base on https://github.com/gl-inet/uboot-ipq60xx

## Build for Ubuntu

PS: The mbn scripts run with python2.7, you should install and switch to python2.7

```bash
sudo bash -c  "apt update && apt install git python build-essential device-tree-compiler -y"
```

```
git clone https://github.com/copilot-is/uboot-ipq60xx
cd uboot-ipq60xx/
./build.sh
```

The uboot binary will be: uboot-ipq60xx/JDC_AX1800_Pro_Uboot.mbn

The uboot failsafe HTTP server ip: 192.168.1.1
