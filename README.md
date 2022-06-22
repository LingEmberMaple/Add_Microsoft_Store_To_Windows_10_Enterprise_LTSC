# 为Windows 10 Enterprise LTSC添加微软商店
适用于Windows 10 Enterprise LTSC

## 下载安装包及依赖包
打开网址：https://store.rg-adguard.net/

分别粘贴以下网址至文本框，点击选择框，调整发布频道至Retail并点击复选框以获取安装包及依赖包的下载链接：
- https://www.microsoft.com/store/productId/9WZDNCRFJBMP
- https://www.microsoft.com/store/productId/9NBLGGH4NNS1
- https://www.microsoft.com/store/productId/9NBLGGH4LS1F
- https://www.microsoft.com/store/productId/9WZDNCRD1HKW

下载如下安装包及依赖包的最新版本（后缀名为appx、appxbundle、msixbundle且不为BlockMap、eappxbundle、emsixbundle）：
- Microsoft.NET.Native.Framework.*_*_*_*.*
- Microsoft.NET.Native.Runtime.*_*_*_*.*
- Microsoft.UI.Xaml.*_*_*_*.*
- Microsoft.VCLibs.*_*_*_*.*
- Microsoft.WindowsStore_*_*_*_*.*
- Microsoft.DesktopAppInstaller_*_*_*_*.*
- Microsoft.StorePurchaseApp_*_*_*_*.*
- Microsoft.XboxIdentityProvider_*_*_*_*.*

## 开始安装
以管理员身份运行Windows PowerShell

输入并按下回车键：`cd {安装包及依赖包所在文件夹路径}`

按次序输入以下命令并按下回车键：
```
Add-AppxPackage .\Microsoft.NET.Native.Framework.*_*_*_*.*
Add-AppxPackage .\Microsoft.NET.Native.Runtime.*_*_*__*.*
Add-AppxPackage .\Microsoft.UI.Xaml.*_*_*__*.*
Add-AppxPackage .\Microsoft.VCLibs.*_*_*__*.*
Add-AppxPackage .\Microsoft.WindowsStore_*_*_*_*.*
Add-AppxPackage .\Microsoft.DesktopAppInstaller_*_*_*_*.*
Add-AppxPackage .\Microsoft.StorePurchaseApp_*_*_*_*.*
Add-AppxPackage .\Microsoft.XboxIdentityProvider_*_*_*_*.*
```
