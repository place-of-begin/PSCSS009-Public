# PSCSS009 Public Preview

PSCSS（Planetary System Calendar Simulation System）是一款面向世界观创作者的模拟工具。

它尝试把：

自然参数  
→ 天体运行  
→ 昼夜与周期  
→ 文明观测  
→ 历法制度

连接成一条可计算、可解释的世界构建链路。

## 当前版本

这是 PSCSS V009 的公开测试版本。

目前主要支持：

- 单恒星、单行星、单卫星系统
- 三维轨道位置与速度
- 自转轴与黄赤交角
- 行星与卫星姿态传播
- 太阳日、朔望月等自然周期计算
- 阳历、阴历、阴阳合历
- 闰日、闰月与多年历法编排
- 文明形成、历法建立和历法改革时间轴
- 文明日期和日历显示
- JSON项目保存与重新打开
- TXT、Markdown、CSV、AI提示词和截图导出

## 项目目标

PSCSS 的长期目标并不只是模拟现实天体。

未来希望允许世界观设计者定义不同的自然规律，例如：

- 周期变化的有效引力
- 特殊物质造成的异常引力
- 魔力潮汐
- 超自然作用力
- 非固定天文周期

并继续观察这些自然规律如何影响文明所观察到的世界、历法和历史。

## 当前状态

本版本仍处于早期测试阶段。

可能存在：

- UI与UX不完善
- 参数解释不足
- 部分功能尚未开放
- 边界情况Bug
- 性能问题

如果你愿意测试，非常欢迎反馈：

- 哪一步最难理解
- 哪些参数不知道如何填写
- 哪些结果对你的世界观设计最有帮助
- 遇到的Bug
- 希望增加的功能

## Source code

当前核心源代码暂未开放。

本仓库主要用于公开测试版本发布、说明和问题反馈。

## License

No open-source license is currently granted.


## macOS 用户请注意
## Note for macOS Users

当前测试版尚未完成 Apple Developer ID 签名与公证，因此 macOS 可能会阻止应用首次启动。

This preview build is not yet signed and notarized with an Apple Developer ID, so macOS may block the app the first time you try to open it.

如果你确认应用来自本项目，可以按以下方式手动允许启动：

If you trust that this app comes from this project, you can allow it manually:

1. 先双击应用并尝试打开一次。  
   Double-click the app and try to open it once.

2. 打开：  
   **系统设置 → 隐私与安全性**  
   Open:  
   **System Settings → Privacy & Security**

3. 向下滚动，找到关于该应用被阻止的提示。  
   Scroll down until you see a message saying the app was blocked.

4. 点击：  
   **仍要打开 / Open Anyway**

5. 再次确认打开。  
   Confirm that you want to open the app.

通常只需要执行一次，之后即可正常启动。

You normally only need to do this once. After that, the app should open normally.

如果仍然无法启动，请把 macOS 版本、Mac 型号以及系统提示截图反馈给我。

If the app still does not start, please send me your macOS version, Mac model, and a screenshot of the system message.
