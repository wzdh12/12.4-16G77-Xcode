# 12.4-16G77-Xcode-
问题描述
iphone升级到12.4，发现XCode无法真机调试。原因是XCode版本低于真机版本，可以更新XCode来解决。但也可以使用如下方法来解决:

1.在本仓库下载12.4-16G77压缩包

2.在应用程序找到Xcode.app,右键，根据下面路径依次进入
  Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport
  
3.把压缩包解压放进文件夹,如下图片

![image](https://github.com/wzdh12/12.4-16G77-Xcode-/blob/master/images/wechat_image.png)

4. 重启XCode。 搞定，收工。
