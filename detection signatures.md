## 文件熵（shannon entropy）

使用sigcheck（微软提供）可计算。

```c
.\sigcheck.exe -h -a "file_path"
```

使用项目https://github.com/merces/entropy更针对更快：

```c
.\entropy.exe "file_path"
```

超过7.2往往可疑、恶意



## 数字签名

使用signtool.exe可验证、移除程序数字签名

移除：

```
"C:\Program Files (x86)\Windows Kits\10\bin\10.0.17763.0\x64\signtool.exe" remove /s "D:\zz_installers\Everything test.exe"
```

