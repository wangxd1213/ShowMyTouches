# ShowMyTouches
The tweak that displays visual indicators for touch interactions on the screen.

## Screenshots

| Settings | Multitouch | Color picker | Modified touch |
|---|---|---|---|
| ![1](https://github.com/user-attachments/assets/017cc79c-98c0-4196-a67a-78e0da6bf411) | ![2](https://github.com/user-attachments/assets/baca36a6-3dac-4f70-8820-ef8b7586284b) | ![3](https://github.com/user-attachments/assets/ddcbac63-b654-4cb2-952b-af21682c31c1) | ![4](https://github.com/user-attachments/assets/46ac42ba-3c08-4775-8aa0-eedf73a02dfe) |

## ShowMyTouches currently supports:
  <li>Rootful, Rootless and Roothide jailbreaks</li>
  <li>Displaying interactions always or during screen recording only</li>
  <li>Multitouching</li>
  <li>Color picker</li>
  <li>Display configuration</li>

<br>

**ShowMyTouches preferences can be found in the iOS Settings, does not require respring**


# Credits
Special thanks to [**Artem Kasper** (@Kesa2773)](https://github.com/Kesa2773) for the inspiration and main hook code


# ShowMyTouches

> **在 iOS 屏幕上显示触控指示器的越狱插件，适合录屏、演示和教学场景。**

---

## ✨ 项目简介

ShowMyTouches 是一款轻量级的 iOS 越狱插件，能够在屏幕上实时显示手指触控的视觉反馈。适用于录制屏幕、应用演示、教程教学等场景。

插件支持自定义触控指示器的颜色、大小、边框样式和动画效果，兼容多点触控，并支持选择仅在屏幕录制时启用。

---

## 🛠 功能特点

- **触控可视化**  
  屏幕上实时显示手指触控位置，支持多点同时显示。
  
- **自定义外观**  
  可调整触控指示器的颜色、边框颜色、大小、圆角、边框宽度。

- **动画效果**  
  手指离开屏幕后，触控指示器自动执行渐隐放大动画，视觉效果流畅自然。

- **录屏识别**  
  可选择只在系统录屏时启用触控指示器，录屏以外保持隐藏。

- **支持多环境**  
  兼容 Rootful 越狱、Rootless 越狱和 roothide 环境。

---

## 📥 安装方式

1. 添加源（如果使用公开源发布时）：
https://your-repo-url.com/

2. 在 Sileo、Zebra 等越狱应用中搜索并安装 **ShowMyTouches**。
3. 安装完成后，前往系统「设置」中找到 ShowMyTouches 进行配置。

或者手动编译安装：
```bash
git clone https://github.com/你的GitHub账户/ShowMyTouches.git
cd ShowMyTouches
make package install

配置项 | 说明 | 默认值
启用指示器 (enabled) | 是否启用触控显示 | ✅ 开启
仅在录屏时启用 (recording) | 仅在录屏状态下显示触控指示器 | ❌ 关闭
触控颜色 (touchColor) | 触控指示器填充颜色 | 系统次要标签色
边框颜色 (borderColor) | 触控指示器边框颜色 | 灰色
动画持续时间 (duration) | 手指离开后渐隐动画的时间（秒） | 0.3
指示器大小 (touchSize) | 触控指示器的宽高（pt） | 40
圆角半径 (touchRadius) | 指示器圆角大小（pt） | 20
边框宽度 (borderWidth) | 边框线条宽度（pt） | 3.0

安装后默认启用，无需额外设置即可生效。

若启用「仅在录屏时显示」，需在系统的屏幕录制功能开始录制后，触控指示器才会显示。

触控指示器支持多点触控，随手指移动自动跟随。



本插件仅适用于越狱环境。

支持 iOS 13 - iOS 17，但在 iOS 13 设备上，建议关闭「仅在录屏时显示」选项，以避免因系统框架差异导致指示器不显示。

使用过程中如遇问题，欢迎提交 Issue 或 Pull Request。
