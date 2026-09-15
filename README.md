# 大镖客3

西部题材方块风格动作小游戏，提供 Windows 电脑版和 Android 手机版。当前版本 1.6。

## 下载

安装包见 [Releases 下载页面](https://github.com/diananjiantie/dabiaoke3/releases/tag/v1.6)。Windows 可下载完整 ZIP 解压后运行，或使用独立 EXE；Android 下载 APK 安装。两端均支持离线游玩。

- Windows：第三人称、Ctrl 视角切换、鼠标瞄准、WASD 移动。
- Android：Android 8.0+，横屏，左摇杆移动、右摇杆转镜头、独立开火与动作键，支持多指操作、灵敏度和画质调节。
- Android APK 与原 com.arthur.frontier 版本使用相同签名。请直接覆盖安装，先卸载会删除存档。
- 安卓本机 JSON 存档与电脑 XML 存档不互通。

## 游戏内容

前三关与列车追击的20波/无尽模式；城镇、居民、帮派、赏金任务、骑马、三城铁路、远岛航班、银行和马车抢劫、警察通缉、监狱劫狱与挖墙逃脱、钓鱼出售和房屋建造。画面包含昼夜、太阳月亮云星、煤油灯和阵雨。

1.6 电脑版修复了飞机朝向、起降高度和镜头，并整理莱特式双翼飞机模型；包括此前的暂停输入、列车朝向和世界比例修复。安卓通过独立WebGL渲染移植相应风格和主要更新，操作与界面针对触屏适配。

## 源码

- `Dabiaoke3-1.6-Windows-Source.zip`：C# Windows 工程，运行 `build.cmd` 构建。
- `Dabiaoke3-1.6-Android-Source.zip`：离线安卓容器、WebGL画面及JavaScript规则。解压后查看 README 获取构建方式。
- `RELEASE_NOTES.md`：1.6 发布说明。

源码不包含签名私钥、密码、个人存档、JDK或Android SDK。

## 验证范围

电脑版通过3D、瞄准、铁路净空、暂停输入、飞行及存档回归测试。手机版通过规则、多指事件、桌面浏览器3D画面和音频解码测试，APK签名与资源哈希校验通过；尚未进行实体安卓手机测试，不承诺具体机型的帧率。

## 制作人员

不死战狼、点按。

