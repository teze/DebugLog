DebugLog
========

Create a simple and more understandable Android logs. 


#Why?

android.util.Log is the most usable library of the Android. But, when the app released on the market, some important information is clearly forgotten by the developer. 
All logs are disabled by DebugLog when the app is released.  

And plus, it provides more understandable DDMS logs for developers.


#Usage

#####Traditional android.util.Log usage:
```java 
public static final String TAG = "MyApp or MyClass name";

void myFunc(){
	android.util.Log.i(TAG, "my message");
}
```

Generally, this logs location forgotten after first day:) if the location hasn't been defined in log message.

#####DebugLog usage:
```java

void myFunc(){
	DebugLog.e("simple log from myFunc()");
}

```

no tags, and no any information. Just write your logs.

It shows useful data;
![Screenshot](https://raw.github.com/MustafaFerhan/DebugLog/master/DebugLog-Demo/assets/ss2.jpg)
![Screenshot](https://raw.github.com/MustafaFerhan/DebugLog/master/DebugLog-Demo/assets/ss1.jpg)


#Contributing

Want to contribute? You are welcome!

#Licence
#####The Unlicense
Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

For more information, please refer to <http://unlicense.org/>
