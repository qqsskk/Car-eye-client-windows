## 项目说明
本项目使用VS2017基于.NET4.0框架编写, 目标平台选择的为X86,因为拉取视频需要调用C++库, 为了兼容32位与64位系统.  
* 运行本项目时需要将Assets目录下的car_img文件夹复制到运行目录中以便在地图中显示车辆图标.
* 将Assets目录下libCarEyePlayer文件夹中的所有dll库文件复制到运行目录中以便进行视频预览.
### 实现功能
* 用户的登陆功能
* 车辆的实时位置查看
* 视频实时监控
* 定时位置信息获取
### 引用库说明
* 主窗体布局控件使用的是开源控件库DockPanelSuite,  
可在NuGet控制台中输入命令:Install-Package DockPanelSuite -Version 3.0.2即可安装.
* 地图控件使用的为本项目组中的CarEyeMap控件.
* 视频预览控件使用本开源项目中的libCarEyePlayer库.