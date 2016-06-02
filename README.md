# SpringIndicator
![icon](https://raw.githubusercontent.com/chenupt/SpringIndicator/master/img/icon.png)

An indicator like Morning Routine guide.It was originally based on [BezierDemo](https://github.com/chenupt/BezierDemo).

The sample app: [click me](http://riontech.com/SpringIndicator/sample-debug.apk)

![gif](http://riontech.com/SpringIndicator/demo.gif)

#Usage
---
Add the dependency to your build.gradle.
```
dependencies {
    compile 'com.github.chenupt.android:springindicator:1.0.2@aar'
}
```
Add the indicator to your layout.

```
<github.chenupt.springindicator.SpringIndicator
            android:id="@+id/indicator"
            android:layout_width="match_parent"
            android:layout_height="100dp"
            app:defaultMargin="30dp"
            app:endMargin="40dp"
            app:siIndicatorColor="@color/colorPrimary"
            app:siIndicatorColors="@array/indicator_colors"
            app:siSelectedTextColor="@android:color/white"
            app:siTextColor="@color/colorPrimaryDark"
            app:siTextSize="18sp"
            app:startMargin="40dp" />
```
Setup with your viewPager.
```
springIndicator.setViewPager(viewPager);
```
[All xml attributes.](https://github.com/chenupt/SpringIndicator/blob/master/lib%2Fsrc%2Fmain%2Fres%2Fvalues%2Fattrs.xml)

Updated By
---
 * Keyur - <keyuraashra@gmail.com>

Developed By
---
 * Chenupt - <chenupt@gmail.com>
 * G+ [chenupt](https://plus.google.com/u/0/109194013506774756478)
 * 微博：[chenupt](http://weibo.com/p/1005052159173535/home)
 * QQ：753785666

License
---

    Copyright 2015 chenupt

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


