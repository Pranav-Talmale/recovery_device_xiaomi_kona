# OrangeFox device tree for Xiaomi Mi 11X / Redmi K40 / POCO F3 (alioth)
For building OrangeFox Recovery for Xiaomi Mi 11X / Redmi K40 / POCO F3

The Xiaomi Mi 11X (codenamed _"aliothin"_) and Redmi K40 / POCO F3 (codenamed _"alioth"_) are mid range smartphones from Xiaomi.

## Device specifications

| Device       | Xiaomi Mi 11X / Redmi K40 / POCO F3         |
| -----------: | :------------------------------------------ |
| SoC          | Qualcomm SM8250 Snapdragon 870 5G           |
| CPU          | 8x Qualcomm® Kryo™ 585 up to 2.84GHz        |
| GPU          | Adreno 650                                  |
| Memory       | 8GB / 6GB  (LPDDR 5)                        |
| Shipped Android version | 11                               |
| Storage      | 128GB  (UFS 3.1)                            |
| Battery      | Li-Po 4520 mAh, non-removable               |
| Dimensions   | 163.7 x 76.4 x 7.8 mm                       |
| Display      | 1080 x 2400 (20:9), 6.67 inches             |

## Device picture

![Xiaomi Mi 11X](https://i01.appmifile.com/webfile/globalimg/7/7BFCB70B-C506-E089-8591-9F2A15CA61FE.png)

## Features

**Works**

- Booting.
- **Decryption** (Android 12+)
- ADB
- MTP
- OTG
- vA/B partition functions
- Vibration

Mi 11X / Redmi K40 / POCO F3 uses a Virtual A/B Partition Scheme!

## Compile

You can find a full compile guide for OrangeFox [Here](https://wiki.orangefox.tech/en/dev/building)

Lunch command :
```
lunch twrp-alioth_eng && mka adbd bootimage
```



## Credits
- [Original Tree By Nebrassy](https://github.com/TeamWin/android_device_xiaomi_alioth)
- [Immensity kernel](https://github.com/UtsavBalar1231/kernel_xiaomi_sm8250.git)
