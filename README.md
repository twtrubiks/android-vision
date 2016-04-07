# Android Vision API Samples
Android 相機 人臉偵測 :memo:

## 說明
* FaceTracker <br>
覺得蠻有趣的，就隨手記錄了一下:memo:。<br>
這個範例程式會開啟手機的相機，然後透過相機進行人臉偵測，<br>
會偵測<b> 左右眼是否睜開眼睛 </b>以及<b> 是否有微笑 </b> ( 數值最高為1 ) <br>
測試的手機為三星note2，Android 版本為 4.4.4<br>
我將它匯出成 APK，方便大家使用 ( 就不用再打開Android Studio重新編譯 ) <br>
apk下載點:  [FaceTracker.apk](https://app.box.com/s/n89v3jl02uq6urh9cp4i226cy0hbwvcc)<br>
以下圖片為在自己手機上的 demo<br>
![alt tag](http://i.imgur.com/wfhE0xw.png)
![alt tag](http://i.imgur.com/Y6VkfFS.png)
![alt tag](http://i.imgur.com/kSOyE1l.jpg)<br>
辨識率蠻精準的，多人也是可以成功的辨識出來<br>
更多可參考 [官網](https://developers.google.com/vision/face-detection-concepts#face_orientation)的說明<br>

Android Vision API Samples
============

These samples demonstrate the vision API for detecting faces and barcodes.

Introduction
------------

Pre-requisites
--------------
 Android Play Services SDK level 26 or greater.

Getting Started
---------------
The samples build using Gradle in Android Studio.  There is no special
configuration required.

Support (Post Release)
-------

For General questions and discussion on StackOverflow:
- Stack Overflow: http://stackoverflow.com/questions/tagged/android-vision

If you've found an error in this sample, please file an issue:
https://github.com/googlesamples/android-vision/issues

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub.

License
-------

Copyright 2015 Google, Inc. All Rights Reserved.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
