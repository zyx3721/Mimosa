# Mimosa Dark - Conky Theme

一个精美的 Conky 桌面监控主题，属于 Leonis Conky 主题包的一部分。

![预览图](preview.png)

## 作者信息

- **作者**: Closebox73
- **版本**: 4.0
- **变体**: Verdant Celsius
- **许可证**: GPLv3

## 功能特性

- 🕐 时间和日期显示
- 🌤️ 实时天气信息（温度、湿度、风速、天气状况）
- 📶 网络状态监控（WiFi SSID、上传/下载速度）
- 💻 系统状态监控（CPU、内存、电池、温度）
- 💾 存储使用情况（带图形化进度条）
- 🎵 媒体播放器控制（显示当前播放信息）
- 🎨 精美的圆环图形显示

## 文件结构

```
Mimosa/
├── Mimosa.conf          # Conky 主配置文件
├── start.sh             # 启动脚本
├── preview.png          # 预览图
├── LICENSE              # GPLv3 许可证
├── Changelog            # 更新日志
├── Donate.txt           # 捐赠信息
├── source.txt           # 源码来源
├── assets/
│   └── bg.png           # 背景图片
├── fonts/
│   ├── Inter-VariableFont_slnt,wght.ttf
│   ├── BebasNeue-Regular.ttf
│   ├── Abel.zip
│   └── feather.ttf
├── lib/
│   ├── rings_rounded.lua  # 圆环图形绘制脚本
│   └── disk_bar.lua       # 磁盘使用条形图脚本
└── scripts/
    ├── weather-v4.0.sh    # 天气数据获取脚本
    ├── playerctl-info.sh  # 媒体播放器信息脚本
    ├── ssid               # WiFi SSID 获取脚本
    └── cputempf.sh        # CPU 温度获取脚本
```

## 许可证

本项目基于 GPLv3 许可证发布。详情请查看 [LICENSE](LICENSE) 文件。

## 致谢

- 作者: [Closebox73](https://twitter.com/closebox73)
- 来源: [Pling](https://www.pling.com/p/1869486/)
