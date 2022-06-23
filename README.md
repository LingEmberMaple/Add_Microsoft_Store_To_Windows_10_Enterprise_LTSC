# 为Windows 10 Enterprise LTSC添加Microsoft Store
适用于Windows 10 Enterprise LTSC

## 自动安装
施工中

## 手动安装
###### 下载安装包及依赖包
打开网址：https://store.rg-adguard.net/

分别粘贴以下网址至网站文本框，点击选择框，调整发布频道至Retail并点击复选框以获取安装包及依赖包的下载链接：
- https://www.microsoft.com/store/productId/9WZDNCRFJBMP
- https://www.microsoft.com/store/productId/9NBLGGH4LS1F
- https://www.microsoft.com/store/productId/9WZDNCRD1HKW

下载如下安装包及依赖包的最新版本（后缀名为appinstaller、appx、appxbundle、msix、msixbundle）：
- Microsoft.NET.Native.Framework.1.3*
- Microsoft.NET.Native.Framework.2.2*
- Microsoft.NET.Native.Runtime.1.3*
- Microsoft.NET.Native.Runtime.2.2*
- Microsoft.UI.Xaml.2.7*
- Microsoft.VCLibs.140.00*
- Microsoft.WindowsStore*
- Microsoft.StorePurchaseApp*
- Microsoft.XboxIdentityProvider*

###### 开始安装
以管理员身份运行Windows PowerShell

输入并按下回车键：`cd {安装包及依赖包所在文件夹路径}`

按次序输入以下命令并按下回车键：
```
Add-AppxPackage .\Microsoft.NET.Native.Framework.1.3*
Add-AppxPackage .\Microsoft.NET.Native.Runtime.1.3*
Add-AppxPackage .\Microsoft.NET.Native.Framework.2.2*
Add-AppxPackage .\Microsoft.NET.Native.Runtime.2.2*
Add-AppxPackage .\Microsoft.UI.Xaml.2.7*
Add-AppxPackage .\Microsoft.VCLibs.140.00*
Add-AppxPackage .\Microsoft.StorePurchaseApp*
Add-AppxPackage .\Microsoft.XboxIdentityProvider*
Add-AppxPackage .\Microsoft.WindowsStore*
```

## 安装完成
如有问题请提交Issue
