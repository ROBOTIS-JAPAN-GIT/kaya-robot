# kaya-robot(NVIDIA Original)

Kaya is an open-source robot powered by NVIDIA's Isaac SDK and the Jetson Nano. 

This repository contains 3D-printable and editable CAD files in the `cad-files` folder (STL, STEP, IGES), as well as a complete bill of materials and assembly instructions for [NVIDIA Kaya](doc/assemble_kaya.md) in the `doc` folder.

![image](doc/images/kaya_robot.jpg)

Kaya is intended to provide an accessible starting point for robotics development, and a number of sample apps for Kaya come packaged with the Isaac SDK.

For more information on Kaya and the Isaac SDK, see the [NVIDIA Isaac SDK Documentation](https://docs.nvidia.com/isaac/isaac/doc/index.html).

You can also join NVIDIA's developer community to ask questions and share your projects on the [Isaac SDK Forums](https://devtalk.nvidia.com/default/board/375/sdk/)!

# kaya日本版
## 1.概要
KayaはNVIDIA Isaac SDK及びJetson Nanoためのアドバンスド研究用プラットフォームです。<br>
kaya日本版は、ROBOTIS Japanの手によって複数の部品を日本で入手しやすいものに置換する、足回りのモータを最新型に換装するなどいくつかの改良を施してあります。<br>
改良した内容は、Isaak SDK 2019.3から公式にサポートされています。<br>
最新のIsaac SDK 2020.1での動作確認済みです。<br>
![nvidia_kaya_jp](https://e-shop.robotis.co.jp/uploads/Items/JP5-0013-000_Kaya_Japan_V1.jpg)

## 2.ハードウェア仕様
| 項目 | 数値 [単位] |
| --- | --- |
|最大移動速度|0.7[m/s]|
|サイズ|(L x W x H)240 x 270 x 230 [mm] (アンテナの突起含む)|
|重量|1.6[kg] (バッテリー込)|
|バッテリー駆動時予想最大動作時間|1.5[h]|
|入力電圧仕様|範囲 : DC10.8~12.6[V],定格 : DC12[V]|
|バッテリー仕様|リチウムポリマーバッテリー LB-012 3セル 11.1V 1800mAh 19.98Wh 5C|
|搭載SBC|NVIDIA Jetson Nano|
|有線I/F|Jetson Nanoに依存する|
|無線I/F|Wi-Fi 802.11ac, Bluetooth4.2(無線LANカードをJetson Nanoに装着)|
|カメラ|Intel RealSence D435(深度カメラ)|
|慣性計測ユニット(IMU)|BOSCH GY-BMI160 6DOF (3軸ジャイロ+3軸加速度)|
|車輪仕様 / 車輪数|3.25inchオムニホイール / 3[個]|
|走行用アクチュエータ|ROBOTIS Dynamixel XC430-W150-T|
|開発環境|NVIDIA Isaac SDK(2019.3以降)|

