# ForzaTelemetryMonitor
English&amp;中文 Forza Horizon &amp; Motorsport telemetry monitor for  — live charts, G-Force, track map, replay &amp; more. Built with .NET 8 WPF + SkiaSharp.

[中文介绍](README-中文.md)

1. Language currently supports English and Chinese.
2. Compatible with Forza Motorsport and Horizon series (likely also supports future Horizon 6).
3. Multi-chart / Data merging / Free drag-and-drop layout.
4. Special panels: Dashboard / G-Force graph / Track map / Power curve, etc.
5. Supports replay / Speed control / Frame-by-frame stepping / Save and load.

Currently only supports Windows 64-bit systems.

Built using .NET 8 WPF + SkiaSharp, it retrieves vehicle data via UDP.

In the game, simply enable "Data Out" in the settings, select the format as "Dash", enter 127.0.0.1 as the IP, and 8000 as the port to connect. (Custom IP and port are also supported.)
