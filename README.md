# android_device_xiaomi_whyred-pbrp

PBRP 4.0 for Xiaomi Redmi Note 5

For building PBRP for Xiaomi Redmi Note 5 Global/Pro

To compile

```
$ mkdir pbrp && cd pbrp

$ repo init -u https://github.com/PitchBlackRecoveryProject/manifest_pb --depth=1 -b android-12.1

$ repo sync

$ git clone https://github.com/9QS/android_device_whyred-pbrp -b android-12.1 device/xiaomi/whyred

$ git clone https://github.com/Ancient-Project/android_kernel_xiaomi_whyred 
# Optional but recommended

$ lunch pbrp_whyred-eng && mka recoveryimage
```
The Redmi Note 5 Pro (codenamed _"whyred"_) are high-end mid-range smartphones from Xiaomi.

Xiaomi Redmi Note 5 Pro was announced and released in February 2018.

## Device specifications

| Device       | Xiaomi Redmi Note 5 Pro                         |
| -----------: | :---------------------------------------------- |
| SoC          | Qualcomm SDM660 Snapdragon 636                  |
| CPU          | 8x Qualcomm® Kryo™ 260 up to 1.8GHz             |
| GPU          | Adreno 509                                      |
| Memory       | 4GB / 6GM RAM (LPDDR4X)                         |
| Shipped Android version | 7.1.1                                |
| Storage      | 64GB eMMC 5.1 flash storage                     |
| Battery      | Non-removable Li-Po 4000 mAh                    |
| Dimensions   | 158.6 x 75.4 x 8.05 mm                          |
| Display      | 2160 x 1080 (18:9), 5.99 inch                   |
| Rear camera 1 | 12MP, 1.25-micron pixels, f/2.2 Dual LED flash |
| Rear camera 2 | 5MP, 1.12-micron pixels, f/2.0                |
| Front camera | 20MP, 1-micron pixels, f/2.2 1080p 30 fps video, Selfie-light|

## Device picture

![Xiaomi Redmi Note 5 Pro](https://www1-lw.xda-cdn.com/files/2018/02/Xiaomi-Redmi-Note-5-and-Redmi-Note-5-Pro-Forums-now-Open.png)
