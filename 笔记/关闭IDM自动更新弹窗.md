## 1. 打开注册表编辑器

按下 `Win + R` 组合键，打开运行。输入 `regedit`并点击 “确定” ，打开注册表编辑器。
## 2. 修改LstCheck项
在注册表中，导航到路径：`计算机\HKEY_CURRENT_USER\SOFTWARE\DownloadManager`，在右边找到 `LstCheck`项（这是控制 IDM 自动更新的注册表项），双击该项并将数值数据改为 0 即可。

  
![image.png](http://tuchuang.nicebb.cc/picture20240906132614.png)

![image.png](http://tuchuang.nicebb.cc/picture20240906132626.png)

## 3. 重启电脑，确保生效