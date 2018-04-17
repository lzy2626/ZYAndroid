# ZYAndroid
[![](https://jitpack.io/v/lzy2626/ZYAndroid.svg)](https://jitpack.io/#lzy2626/ZYAndroid)
How to
To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

gradle
maven
sbt
leiningen
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.lzy2626:ZYAndroid:v1.0'
	}
2018-04-17 v1.0

**网络工具类NetUtils**
```
判断网络是否连接
isConnected(Context context)
return boolean

判断是否是wifi连接
isWifi(Context context)
return boolean

打开网络设置界面
openSet(Activity activity)
```
