**其他语言版本: [English](readme.md), [中文](README_zh.md).**
<p align="center">
  <img src="/images/wled_logo_akemi.png">
  <a href="https://github.com/Aircoookie/WLED/releases"><img src="https://img.shields.io/github/release/Aircoookie/WLED.svg?style=flat-square"></a>
  <a href="https://raw.githubusercontent.com/Aircoookie/WLED/master/LICENSE"><img src="https://img.shields.io/github/license/Aircoookie/wled?color=blue&style=flat-square"></a>
  <a href="https://wled.discourse.group"><img src="https://img.shields.io/discourse/topics?colorB=blue&label=forum&server=https%3A%2F%2Fwled.discourse.group%2F&style=flat-square"></a>
  <a href="https://discord.gg/QAh7wJHrRM"><img src="https://img.shields.io/discord/473448917040758787.svg?colorB=blue&label=discord&style=flat-square"></a>
  <a href="https://kno.wled.ge"><img src="https://img.shields.io/badge/quick_start-wiki-blue.svg?style=flat-square"></a>
  <a href="https://github.com/Aircoookie/WLED-App"><img src="https://img.shields.io/badge/app-wled-blue.svg?style=flat-square"></a>
  <a href="https://gitpod.io/#https://github.com/Aircoookie/WLED"><img src="https://img.shields.io/badge/Gitpod-ready--to--code-blue?style=flat-square&logo=gitpod"></a>

  </p>

# 欢迎来到我的项目 WLED！ ✨

ESP8266/ESP32 网络服务器的快速且功能丰富的实现，用于控制 NeoPixel（WS2812B、WS2811、SK6812）LED 或基于 SPI 的芯片组，如 WS2801 和 APA102！

## ⚙️ 特点
- WS2812FX 库包含 100 多种特效  
- FastLED 噪音效果和 50 种调色板
- 具有颜色、效果和分段控制的现代用户界面
- 为 LED 灯串的用户定义部分设置不同的效果和颜色
- 设置页面-通过网络配置
- 接入点和站点模式 - 自动故障安全 AP
- 每个实例最多 10 个 LED 输出
- 支持 RGBW 灯带
- 最多 250 个用户预设，可轻松保存和加载颜色/效果，支持循环浏览。
- 可以使用预设自动执行 API 调用
- 夜灯功能（逐渐变暗）
- 完全 OTA 软件更新 (HTTP + ArduinoOTA)，可密码保护
- 可配置模拟时钟（通过 usermods 支持 Cronixie、7 段和 EleksTube IPS 时钟）
- 可配置自动亮度限制以确保安全操作
- 基于文件系统的配置，可以更轻松地备份预设和设置

## 💡 支持灯光控制接口
- 适用于 [安卓](https://play.google.com/store/apps/details?id=com.aircoookie.WLED) 和 [苹果](https://apps.apple.com/us/app/wled/id1475695033)程序
- JSON 和 HTTP 请求 API
- MQTT   
- E1.31, Art-Net, DDP and TPM2.net
- [diyHue](https://github.com/diyhue/diyHue) (Wled 由 diyHue 支持，包括 udp 下的 Hue Sync Entertainment。感谢 [Gregory Mallios](https://github.com/gmallios))
- [Hyperion](https://github.com/hyperion-project/hyperion.ng)
- 实时 UDP 
- Alexa 语音控制（包括调光和颜色）
- 与飞利浦 Hue 灯同步
-  Adalight（通过串行的 PC ambilight）和 TPM2
-  同步多个 WLED 设备的颜色（UDP 通知程序）
-  红外遥控器（24 键 RGB，需要接收器）
-  简单的计时器/时间表（支持 NTP 时间、时区/DST）

## 📲 快速入门指南和文档

请参阅我们官方网站上的文档！ (https://kno.wled.ge)

[在此页面上](https://kno.wled.ge/basics/tutorials/) 您可以找到出色的教程和工具来帮助您启动和运行新项目！

## 🖼️ 用户界面
<img src="/images/macbook-pro-space-gray-on-the-wooden-table.jpg" width="50%"><img src="/images/walking-with-iphone-x.jpg" width="50%">

## 💾 兼容硬件

[点击这里](https://kno.wled.ge/basics/compatible-hardware)!

## ✌️ 其他
 [根据 MIT 许可证授权，版权归这里所有！](https://kno.wled.ge/about/contributors/)!

加入 Discord 服务器讨论有关 WLED 的一切！

<a href="https://discord.gg/QAh7wJHrRM"><img src="https://discordapp.com/api/guilds/473448917040758787/widget.png?style=banner2" width="25%"></a>

[查看 WLED论坛！](https://wled.discourse.group)!  

[您也可以向我(mailto:dev.aircoookie)发送邮件，](mailto:dev.aircoookie@gmail.com), 但请务必仅在您想私下与我交谈时才这样做。
如果 WLED 确实能让您心情愉悦，那么您可以[![](https://img.shields.io/badge/send%20me%20a%20small%20gift-paypal-blue.svg?style=flat-square)](https://paypal.me/aircoookie)


免责声明：

如果您容易患光敏性癫痫，我们建议您不要使用此软件。
如果您仍想尝试，请不要使用频闪、灯光或噪音模式或高效果速度设置。

根据 MIT 许可证，我不对您或任何其他人或设备造成的任何损害承担任何责任。
