# GaodeMap-APITest
 ## 主要功能

1. 注册时账号通过正则表达式判断是否为正确的手机号
2. 密码必须为6位以上的数字或字母组合
3. 注册后跳回登陆界面，账号密码自动填写
4. 若选中“记住账号密码”框，则会将密码计入缓存，下次打开App时会自动填入（账号填入为默认操作）
5. 登录后显示地图，点击“开始”按钮可启动小车，移动到地图上其他位置时，点击“继续”，则会返回小车运行的界面
6. 点击定位按钮，会定位到当前位置（需给APP定位权限）
7. 地图缩放和旋转正常，指南针也一切正常

## 注意事项

使用前需在高德开发者控制台创建应用，获取应用的key值

![](https://github.com/Ricky-Chu/GaodeMap-APITest/blob/main/GaoDe-key.png)

将此key值填入AndroidManifest.xml文件meta-data下，具体路径和位置如下：

![](https://github.com/Ricky-Chu/GaodeMap-APITest/blob/main/AndroidManifest-path.png)
