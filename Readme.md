
# 代码块的创建


 对代码块的熟练使用可以减少开发时间，并且不需要每个页面每个类都去重写创建方法。
 
 
## 1、如何添加
选中所编写的代码，比如：

```
/** name */
@property (nonatomic, copy) NSString *name;
```

通过变量替换符<#type#>将类型和变量名替换成可编辑，比如需要将上述代码变成可编辑 将name 写成 <#name#> NSString 写成 <#Class#>即可

```
/** <#name#> */
@property (nonatomic, copy) <#Class#> *<#name#>;
```
此时会变成可编辑状态

![](http://ww1.sinaimg.cn/large/ed0bfc02gy1g4fjygjvezj20lg02sdg3.jpg)

然后选中代码点击右键，点击 Create Core Snippet

![](http://ww1.sinaimg.cn/large/ed0bfc02gy1g4fk0jmontj219a0qwajm.jpg)

此时会自动打开coreSnippet

![](https://github.com/qiuyubude/CoreSnippet/blob/master/Image/image2.png?raw=true)

Title：标题。

Summary：描述文字。

Platform：可以使用的平台（如iOS）。

Language：可以在哪些语言中使用（如 Objective-C）。

Completion Shortcut：快捷方式，以字母开头（支持少数符号，如@）。

Completion Scopes：作用范围，一般写在正确的位置拖动即可，Xcode会自行选择好。

## 2、如何编辑
选中代码块，然后单击即可

![](https://github.com/qiuyubude/CoreSnippet/blob/master/Image/image3.png?raw=true)

## 3、如何删除
选中代码块，快捷键shift+delete

![](https://github.com/qiuyubude/CoreSnippet/blob/master/Image/image4.png?raw=true)

## 4、如何导出
### （1）存储位置
     自定义的代码块保存在此路径下：/Users/UserName/Library/Developer/Xcode/UserData/CodeSnippets 

![](https://github.com/qiuyubude/CoreSnippet/blob/master/Image/image5.png?raw=true)

### （2）文件通用
    可将该路径下的自定义代码块文件进行备份（我是上传至GitHub），然后当Xcode升级或者更换电脑时将文件拷贝到同一目录下即可
    
  简书地址：https://www.jianshu.com/p/fe6ca1e74c1b
    
GitHub地址:https://github.com/qiuyubude/CoreSnippet