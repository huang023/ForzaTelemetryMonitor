# ForzaTelemetryMonitor
English&amp;中文 Forza Horizon &amp; Motorsport telemetry monitor for  — live charts, G-Force, track map, replay &amp; more. Built with .NET 8 WPF + SkiaSharp.

1. 语言目前支持英语和中文。
2. 支持极限竞速和地平线系列（未来地平线6应该也行）
3. 可多图表 / 合并数据 / 自由拖拽排列
4. 仪表盘 / G-Force图 / 轨迹图 / 功率曲线等特殊面板
5. 支持回放 / 倍速 / 逐帧步进 / 保存读取

目前仅支持win64系统。

使用技术.NET 8 WPF + SkiaSharp，通过UDP获取车辆数据。

游戏端只需在设置里开启「数据输出 / Data Out」，格式选 Dash，IP填 `127.0.0.1`，端口填`8000`即可连接。（也可以自定义IP端口）
