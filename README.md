# TWRP Device Tree for Samsung Galaxy S23 Ultra 5G

## Common source:
[Here](https://github.com/archer-private-org/android_device_samsung_sm8550-common.git)

## To build it: 
```bash
. build/envsetup.sh
lunch twrp_dm3q-eng
mka recoveryimage -j$(nproc --all)
```
