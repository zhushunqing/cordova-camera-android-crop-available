cordova-camera-android-crop-available
=====================================

Android下Phonegap/cordova插件拍照、选取相册后支持图片裁切

phonegap/cordova plugin org.apache.cordova.camera allow the user to crop the image function available.

base on cordova-plugin-camera 0.2.8 https://github.com/apache/cordova-plugin-camera

Example:

	cordova create hello com.example.hello HelloWorld

	cd hello

	cordova plugin add https://github.com/zhushunqing/cordova-camera-android-crop-available

	cp -f plugins/org.apache.cordova.camera/example/assets/www/index.html www/index.html

	cordova platform add android

	cordova build android
	or
	cordova run android

	Android Project Files See ./platfrom/android/

OR:

	Eclipse -> New -> Other -> Android Project from Existing Code
	From "./example/"
