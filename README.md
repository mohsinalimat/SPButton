# SPButton
[![Pod Version](http://img.shields.io/cocoapods/v/SPButton.svg?style=flat)](http://cocoadocs.org/docsets/SPButton/)
[![Pod Platform](http://img.shields.io/cocoapods/p/SPPageMenu.svg?style=flat)](http://cocoadocs.org/docsets/SPButton/)
![Language](https://img.shields.io/badge/language-Object--C-ff69b4.svg)

## 安装
```
target 'MyApp' do
  pod 'SPButton', '~> 3.1.0'
end
```

## 如何使用
* 创建(创建的时候就设定图片的位置，也可以之后通过属性imagePosition设置)
```
SPButton *button = [[SPButton alloc] initWithImagePosition:SPButtonImagePositionLeft];
```

* 设置图片位置
```
button.imagePosition = SPButtonImagePositionTop;
```

* 设置图文间距
```
button.imageTitleSpace = 10;
```

## 效果图
![image](https://github.com/SPStore/SPButton/blob/master/F728B222E090608891172DB207F7EF45.jpg)
## 测试演示图(gif)
![image](https://github.com/SPStore/SPButton/blob/master/演示图.gif)
