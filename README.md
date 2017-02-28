# 简介 #
本项目是[SlidingMenu](https://github.com/jfeinstein10/SlidingMenu)的Android Studio版，方便开发者在Android Studio中集成SlidngMenu.

# 使用姿势 #
	//项目下的build.gradle
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
	//app模块下的build.gradle
	dependencies {
	        compile 'com.github.uncleleonfan:SlidingMenu:1.0.0'
	}

