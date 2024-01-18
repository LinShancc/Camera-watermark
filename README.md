# Camera-watermark
# 专业相机水印
Add popular bottom parameter watermarks to photos taken by the camera
给相机拍出的照片添加流行的底部参数水印

Packages that need to be used:
需要用到的包：
- pillow==9.3.0
- pyyaml==6.0
- piexif

Folder Description:
文件夹说明：
- input:存放需要批量处理的照片
- output:处理完的图片输出位置
- logos:相机厂商logo存放位置
- fonts:需要使用的字体存放位置

Function:
功能：
- 显示厂商 logo
- 显示相机机型
- 根据设置显示摄影作者名
- 显示拍摄参数[镜头焦距(非等效)、光圈、快门速度]
- 支持复制 exif 信息到输出的文件中

Results shown:
效果：
![示例图片](images/example.jpg)
