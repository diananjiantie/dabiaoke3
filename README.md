# 大镖客3

当前版本：**1.7 光影优化版**。西部题材方块风格游戏，提供 Windows 电脑版和 Android 手机版，包含章节挑战与开放世界。

## 下载与安装

前往 [1.7 版本下载页](https://github.com/diananjiantie/dabiaoke3/releases/tag/v1.7)，或直接下载：

- [Windows 电脑版 EXE](https://github.com/diananjiantie/dabiaoke3/releases/download/v1.7/Dabiaoke3-1.7-Windows.exe)：下载后直接运行，无需浏览器。
- [Android 手机版 APK](https://github.com/diananjiantie/dabiaoke3/releases/download/v1.7/Dabiaoke3-1.7-Android.apk)：支持 Android 8.0 及以上，安装后可离线游玩。沿用原版签名，可覆盖更新；请保留旧版安装，避免卸载时删除存档。
- [电脑＋手机完整分享包](https://github.com/diananjiantie/dabiaoke3/releases/download/v1.7/Dabiaoke3-1.7-Complete.zip)：包含两端程序、源码、操作说明及测试报告。
- [两端源码 ZIP](https://github.com/diananjiantie/dabiaoke3/releases/download/v1.7/Dabiaoke3-1.7-Sources.zip)：解压后分别查看 `desktop/` 与 `android/`。

旧版 **1.6** 继续保留在 [Releases](https://github.com/diananjiantie/dabiaoke3/releases)，可按需下载。安卓与电脑使用不同存档格式，存档不互通。

## 1.7 更新

- 新增林间丁达尔日光光束和夜间煤油灯暖光，随太阳高度、昼夜和降雨变化。光束采用低开销散射近似，可增强或关闭。
- 两端缓存地形、树木和铁路，减少每帧重复计算；安卓静态顶点保留在 GPU。
- 电脑版减少云层面数，按 **F6 切换画质**、**F7 切换光束**。
- 手机版增加可开关的自动 3D 分辨率调节，保留界面清晰度与持续触控；修复输入清空后的残留开火状态。
- 修正常昼、常夜模式中的天体显示，调整树木与石块，使其避开房屋周围。

既有章节、开放世界玩法及两端原存档格式保留。详细内容见 [发行说明](RELEASE_NOTES.md)。

## 源码

仓库中的 [Dabiaoke3-1.7-Sources.zip](Dabiaoke3-1.7-Sources.zip) 是本版本两端源码归档。解压后：

- `desktop/`：Windows C# 项目、构建脚本与回归测试。
- `android/`：Android 项目、离线游戏资源、构建脚本与测试。

构建方式与依赖见各目录内的 README。发布源码不包含 Android 签名私钥；自行构建需使用自己的签名。

## 验证范围

电脑版已通过 3D、相机、瞄准、铁路、飞机、暂停、存档与画质档位回归测试。手机版已通过规则、多指触控、音效、存档、自动缩放与 WebGL 恢复测试，APK v2/v3 签名校验通过。

**安卓尚未进行实体手机测试，未验证实体手机帧率。** 性能改善不代表所有设备都能达到固定帧率。

## 制作人员

**不死战狼、点按**。
