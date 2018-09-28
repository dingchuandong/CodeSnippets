---
title: 一键导入代码块
date: 2017-11-12 16:58:13
tags: 积累
---
# 一键导入代码块

## 之前弄过代码块，但是每次换电脑或者重装电脑忘记备份就杯具了，最近看网上有个比较方便的方法。

使用:
```
cd CodeSnippets
./createSnippets.sh
成功之后输出:
done
完全退出Xcode后重新新打开Xcode
```

删除代码块:
```
./deleteSnippets.sh
```

清除Xcode 缓存垃圾,释放磁盘存储空间:
```
./clearTempData.sh
```

打开代码块所在位置:
```
./openCodeSnippets.sh
```

```
或者手动打开: Finder->前往->前往文件夹
~/Library/Developer/Xcode/UserData/CodeSnippets/
```

调用 | 实现  
---|---
D Button         | 一键创建UIButton
D TableView|一键创建UITabelView
D Label|一键创建UILabel
D Label+Custom|一键 Label自适应宽高
D PickerView|一键自定义UIPickerView
D Window|一键创建UIWindow
D CornerRadius| 一键设置圆角
D Dispatch_async|一键 子 -> 主 线程(GCD)
D Timer|一键 NSTimer 带暂停/开始
D ImageView |一键 UIImageView 圆角+边框
D Switch  |一键创建 UISwitch 附带 点击Action| { 触发 }
D TextField|一键创建 UITextField<br>自定义 清除按键 img <br>是否密文输入 placeholder|{ 触发 }
D ScrollView|一键创建 UIScrollView |{ 触发 }
D PageControl|一键创建 UIPageControl|{ 触发 }
D Slider|一键创建滑块 附带 值改变 拖动结束 method|{ 触发 }
D /// |一键注释|触发 { }
D interface|一键添加 interface |#import 下面  触发
D Assign|一键 声明 assign 属性  |interface 内触发
D Copy|一键 声明 copy 属性  |interface 内触发
D Weak|一键 weak 属性 |interface 内触发
D Strong |一键 声明 Strong 属性 |interface 内触发
D Mark|一键 mark|触发 {  }
D docPath |一键生成 documentPath|{ 触发 }
D NSNotificationCenter| 一键发送 接收通知 | { 触发 }
D ActivityIndicatorView|一键 正在加载..(菊花)  转起来 暂停|{ 触发 }  
D AlertController|一键创建 警告框 附带 确定 取消 回调|{ 触发 }
D AlertController<br>UserNamePwdTextField|一键创建UIAlertController<br>附带Username/PwdTextField|{ 触发 }
D PlayMusic|一键播放音频文件 |触发 { }
D SegmentedControl<br>duogeyipaianjian | 一键创建一排按键 多格按键 附带点击action |{ 触发 }
D hide_keyboard |一键 点击 view 隐藏键盘| 触发 {  }
D RequestDelegate|一键创建networkRequestDelegate|触发 {  }
D WebView|一键创建 UIWebView 附带Delegate| { 触发 }
D AFN_网络状态改变的时候触发|一键监听网络状态:<br> 蜂窝网络, 无网络,<br> wifi网络变化时触发回调| { 触发 }
D AFN_Upload |利用AFNetworking3.1.0封装的两种上传文件方式|触发 { }
D AFN_Get |一键生成 AFNetworking get 网络请求|触发 { }
D AFN_POST |一键生成 AFNetworking POST 网络请求 带进度|触发 { }
D AFN_Download |一键生成 AFNetworking Download<br>带下载进度 自定义存储filepath |触发 { }
D POST_yuansheng | 一键生成 ios 原生 POST 网络请求,<br>post 参数(可选) <br>自定义请求头 HTTPHeader (可选)<br>支持: application/x-www-form-urlencoded<br>multipart/form-data  两种类型 POST|{ 触发 }
D PCH|一键定义常用宏|#ifndef PrefixHeader_pch<br>#define PrefixHeader_pch<br>触发 D PCH <br>#endif
