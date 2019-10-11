# LoadingBar
#### 基于dialog封装的安卓加载动画
#### 使用方法

```html
loadingView = new LoadingView(this);
//展现
loadingView.show();
//隐藏
loadingView.dismiss();
```
#### 添加下面style到本地stytles.xml中
```html
 <style name="dialog_loading_view" parent="android:style/Theme.Dialog">
        <item name="android:windowFrame">@null</item>
        <item name="android:windowIsFloating">true</item>
        <item name="android:windowIsTranslucent">true</item>
        <item name="android:windowNoTitle">true</item>
        <item name="android:background">@null</item>
        <item name="android:windowBackground">@android:color/transparent</item>
        <item name="android:windowContentOverlay">@null</item>      
        <item name="android:backgroundDimEnabled">true</item>
        <item name="android:backgroundDimAmount">0</item>
    </style>
```
