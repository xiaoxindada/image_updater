# image_updater

**这是一个基于AnyKernel 修改的提供 a, ab, dynamic 分区设备卡刷image的脚本(需要使用twrp)**  
AnyKernel地址: [AnyKernel](https://github.com/osm0sis/AnyKernel3)

## 说明
```
是的你没有看错 这确实可以使动态分区直接卡刷image 从而摆脱电脑和super.img
持的分区: system system_ext vendor product odm
如果觉得image太大 你也可以将其压缩为.gz 然后放入此次脚本
```
## 使用方法
```
git clone https://github.com/xiaoxindada/image_updater.git
mv <image/image.gz path> image_updater/
cd image_updater
rm -rf .git
zip -r image-updater.zip ./*
```
