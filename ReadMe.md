## Device Tree for Nokia 6.1 Plus

Attempting to bring-up from scratch

Brick counter: 13

The Nokia 6.1 Plus/Nokia X6 (codenamed _"Dragon"_, TLA _"DRG_sprout"_) is a mid-range smartphone from Nokia.
It was released in July 2018.

| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Octa-core 4x1.8 & 4x1.6 GHz Kryo 260 (Gold & Silver)                                                                           |
| Chipset                 | Qualcomm SDM660 Snapdragon 636                                                                                                 |
| GPU                     | Adreno 509                                                                                                                     |
| Memory                  | 4/6 GB RAM                                                                                                                     |
| Shipped Android Version | 8.1                                                                                                                            |
| Storage                 | 64 GB                                                                                                                          |
| Battery                 | Non-removable Li-Po 3060 mAh battery                                                                                           |
| Display                 | 1080 x 2280 pixels, 19:9 ratio (~432 ppi density)                                                                              |
| Camera (Back)           | 16 MP, f/2.0, 1.0µm, PDAF, 5 MP, f/2.4, (depth)                                                                                |
| Camera (Front)          | 16 MP, f/2.0, 1/3.1", 1.0µm                                                                                                    |

![Nokia 6.1 Plus](https://fdn2.gsmarena.com/vv/pics/nokia/nokia-x6-3.jpg)


## Dependencies

Run the following commands in your ROM base folder before you build

```git clone https://github.com/Nokia-SDM660/android_external_bson.git -b lineage-17.1 external/bson```

```git clone https://github.com/Nokia-SDM660/android_system_qcom.git -b lineage-17.1 system/qcom```
