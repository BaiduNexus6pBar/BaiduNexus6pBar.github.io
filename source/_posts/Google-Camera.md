---
title: Google Camera
categories:
  - 软件
date: 2018-11-17 11:51:07
updated: 2019-01-10 23:40:00
tags:
author: 神经元
---

### 1.关于Google Play服务  
 **如果您的手机上已经安装有 Gapps，请跳过此节进入下一节**  
  如果手机上没有 Google Play 服务，直接使用谷歌相机会造成闪退。想安装完整的Gapps，请参阅 [未完成]

对于未解锁／不想安装Gapps的用户，可以通过安装microG来使用谷歌相机，在以下链接下载microG：  
[百度云](https://pan.baidu.com/s/112OsDSGCA6iGsHXtB3_YIg) 提取码:n15n （GoogleCamera/com.google.android.gms-13280012.apk）  
或直接从官网下载 Services Core：[Download － microG Project](https://microg.org/download.html)


关于microG：[microG Project](https://microg.org/)  
> The linux-based open-source mobile operating system Android is not only the most popular mobile operating system in the world, it’s also on the way to becoming a proprietary operating system. How is that?
>While the core operating system is still released as part of the Android Open Source Project, the majority of core apps are not. It gets worse: More and more libraries and APIs are only available on phones that run various Google apps pre-installed, effectively locking third-party apps to the Google ecosystem. For these reasons Android is described as being a “look but don’t touch” kind of open.
>At this point, several popular open-source applications already require some of Google’s proprietary libraries to be installed. Increasing demand in the free software community in addition to severe problems in Google’s proprietary software discovered by the Android modding community, have led to the development of a free software clone of Google’s proprietary core libraries and applications - the microG Project was born.
>Although most microG components are far from complete, users are amazed by the results. Free software users got extended application support, privacy-caring users can reduce or monitor data that is sent to Google and especially older phones can expect some battery life improvements. microG is not only used on real devices, but also replaces Google tools in test emulators and is even used in virtual mobile infrastructure.

### 2.Camera API  
 - 对于没有解锁／没有安装 Magisk 的用户，将您的手机打开USB调试并连接至电脑，在电脑的终端中依次输入：   
```bash
adb shell
setprop persist.camera.HAL3.enabled 1
setprop persist.camera.enable 1
```  
关于adb环境配置使用、USB调试。请参阅 [未完成]

 - 对于已经安装了 Magisk 的用户，可以选择安装 Camera2API enable 而不用执行上述步骤，在以下链接下载:

[百度云](https://pan.baidu.com/s/112OsDSGCA6iGsHXtB3_YIg) 提取码:n15n （GoogleCamera/C2API_enabler_v1500.zip）   
或直接从XDA下载： [[Module] Camera2APIenabler](https://forum.xda-developers.com/apps/magisk/module-camera2api-enabler-t3656651)    
关于Magisk，请参阅 [未完成] 或XDA：[Magisk](https://forum.xda-developers.com/apps/magisk)

### 3.Google Camera    
这个地址收集了几乎所有的谷歌相机修改版：[Google Camera Port](https://www.celsoazevedo.com/files/android/google-camera/)    

 一般来说 Arnova 的修改版是最为推荐的，功能也比较齐全：    
[百度云](https://pan.baidu.com/s/112OsDSGCA6iGsHXtB3_YIg) 提取码:n15n （GoogleCamera/GCam-5.1.018-Pixel2Mod-Arnova8G2-V8.3b1.apk）   
[Google Camera Port: Arnova8G2 apks](https://www.celsoazevedo.com/files/android/google-camera/dev-arnova8G2/#apk411)

新版本的Google相机增加了黑科技夜视仪，极大的提升了黑暗环境下的拍照效果。但日常使用尚不是特别稳定：
[百度云](https://pan.baidu.com/s/112OsDSGCA6iGsHXtB3_YIg) 提取码:n15n （GoogleCamera/MGC_6.1.021_V1.apk） 
[Google Camera Port: BSG apks](https://f.celsoazevedo.com/file/gcamera/MGC_6.1.021_V1.apk)  

对于某些极其罕见的特殊情况造成的不兼容，可以尝试 Charles_l 的Nexus6p专版：    
[百度云](https://pan.baidu.com/s/112OsDSGCA6iGsHXtB3_YIg) 提取码:n15n （GoogleCamera/camera_nx_v7.4_ZSL_chromloop.com.apk）   
[Google Camera Port: Charles_l apks](https://www.celsoazevedo.com/files/android/google-camera/dev-charles/)  
