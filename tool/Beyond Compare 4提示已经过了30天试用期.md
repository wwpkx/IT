```
打开Beyond Compare 4，提示已经超出30天试用期限制，解决方法：
1.修改C:\Program Files\Beyond Compare 4\BCUnrar.dll ,这个文件重命名或者直接删除，则会新增30天试用期，再次打开提示还有28天试用期。

2.一劳永逸，修改注册表
1)在搜索栏中输入 regedit   ，打开注册表
2) 删除项目：计算机\HKEY_CURRENT_USER\Software\Scooter Software\Beyond Compare 4\CacheId
```

