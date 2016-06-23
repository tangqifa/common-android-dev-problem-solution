#Android开发中常用问题解决方案
```
Q: Android null requires the IDE to be running with Java 1.8 or later？

A: Edit the file /Applications/Android\ Studio.app/Contents/Info.plist, and remove the 1.6 version (in my case), you may place 1.6+, 1.7+ or 1.8
```
[参考链接](http://stackoverflow.com/questions/35928580/android-n-requires-the-ide-to-be-running-with-java-1-8-or-later)

```
A: App网络框架突然不能用 回到以前也不行？
    compile 'com.squareup.retrofit2:retrofit:2.0.0-beta4'
    compile 'com.squareup.retrofit2:converter-gson:2.0.0-beta4'
Q: 一定要注意这个两个版本号要一致，否则导致请求不成功
```






