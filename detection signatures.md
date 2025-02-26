## 文件熵（shanon entropy）

使用sigcheck（微软提供）可计算。

```c
.\sigcheck.exe -h -a "file_path"
```

使用项目https://github.com/merces/entropy更针对更快：

```c
.\entropy.exe "file_path"
```

超过7.2往往可疑、恶意