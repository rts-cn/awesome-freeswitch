# Awesome FreeSWITCH

[English](README.md) | 简体中文

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Stars](https://img.shields.io/github/stars/rts-cn/awesome-freeswitch?style=flat-square&logo=github)](https://github.com/rts-cn/awesome-freeswitch/stargazers)

一份精选的 FreeSWITCH 资源、模块、框架、库和软件清单。灵感来自 [awesome-go](https://github.com/avelino/awesome-go)。

**收录范围**：与 FreeSWITCH 相关且现在就能用的项目。描述基于各项目自己的说法，略有编辑。只看 API 手册的话，[官方文档](https://developer.signalwire.com/freeswitch)更合适。

## 目录

- [有用的链接](#有用的链接)
- [模块](#模块)
- [库](#库)
- [工具](#工具)
- [资源](#资源)
- [客户端](#客户端)
- [朋友们](#朋友们)
- [其它](#其它)
- [过时](#过时)

## 有用的链接

- [FreeSWITCH](https://freeswitch.org) - FreeSWITCH 社区。
- [ClueCon](https://cluecon.com) - 年度电话与 VoIP 开发者大会，2005 年由 FreeSWITCH 核心团队创办。
- [RTSCon](https://rts.cn/events/) - RTSCon 是一个年度电话与 VoIP 开发者大会，由 FreeSWITCH 中文社区于 2012 年发起，以前叫 FreeSWITCH 开发者沙龙，2020 年改为此名。
- [FreeSWITCH Releases](https://github.com/signalwire/freeswitch/releases/) - FreeSWITCH 发布说明。
- [FreeSWITCH Docs](https://developer.signalwire.com/freeswitch) - FreeSWITCH 官方文档，包括模块参考和 Event Socket 协议说明。
- [freeswitch-docs](https://github.com/signalwire/freeswitch-docs) - 上述文档的源码，发现错误可以直接提 PR。 `MIT`
- [SignalWire](https://signalwire.com) - 提供语音、短信（SMS）和视频高级 API 的弹性云通信平台，由软件定义电信领域的先驱设计。
- [SignalWire Community](https://forum.signalwire.community/) - SignalWire 官方社区论坛的 FreeSWITCH 版块。
- [FreeSWITCH 中文社区](http://www.freeswitch.org.cn) - 面向中文用户的 FreeSWITCH 社区。
- [Kamailio 中文社区](https://www.kamailio.org.cn) - 面向中文用户的 Kamailio 社区。
- [RTS](http://rts.cn) - RTS 实时解决方案社区，涵盖 FreeSWITCH、Kamailio、OpenSIPS、WebRTC 和 AI 等。
- [FreeSWITCH 图书](https://book.dujinfang.com/) - FreeSWITCH 相关的中文图书。
- [FreeSWITCH 培训](http://x-y-t.cn/training.html) - FreeSWITCH 培训课程（中文）。
- [RTS（GitHub）](https://github.com/rts-cn) - RTS 实时通信解决方案。
- [FreeSWITCH（GitHub）](https://github.com/freeswitch) - 一些外围的 FreeSWITCH 模块。
- [XSwitch Free](https://github.com/rts-cn/xswitch-free) - 由 [XSwitch.cn](https://xswitch.cn) 提供的 Docker 镜像，可供学习 FreeSWITCH 使用。

## 模块

- [mod_shine](https://github.com/rts-cn/mod_shine) - 使用 shine 进行 MP3 录音的模块。
- [mod_vnc](https://github.com/rts-cn/mod_vnc) - 与 VNC 交互的模块。 `C`
- [mod_x11](https://github.com/rts-cn/mod_x11) - 与 X11 交互的模块。 `C`
- [mod_aac](https://github.com/rts-cn/mod_aac) - AAC 编解码模块。 `C`
- [mod_unimrcp](https://github.com/freeswitch/mod_unimrcp) - 通过 MRCP 协议连接 ASR/TTS 的模块。 `C`
- [mod_mosquitto](https://github.com/freeswitch/mod_mosquitto) - 通过 Eclipse Mosquitto C 客户端连接 MQTT broker 的 FreeSWITCH 模块。 `C`
- [mod_coreclr](https://github.com/freeswitch/mod_coreclr) - 未来将承载一个基于 .NET Core 3.1 的语言插件模块。 `MIT` `C#`
- [mod_v](https://github.com/seven1240/mod_v) - 用 V 语言编写的 FreeSWITCH 模块。 `V`
- [mod_audio_stream](https://github.com/amigniter/mod_audio_stream) - 生产级的 WebSocket 音频流：把通道音频推送到 WebSocket，并播放返回的音频，常用来连接 FreeSWITCH 和语音识别或 AI 服务。 `C++`

## 库

- [GreenSWITCH](https://github.com/EvoluxBR/greenswitch) - 经生产环境长期验证的 Event Socket 客户端，基于 Gevent。 `Python`
- [TrioSWITCH](https://github.com/space88man/trioswitch) - 基于 Trio 的 Event Socket 客户端实现（源自 GreenSWITCH）。
- [sofia-sip](https://github.com/freeswitch/sofia-sip) - FreeSWITCH 所用的 SIP 协议栈，现由 FreeSWITCH 项目维护。 `LGPL-2.1` `C`
- [spandsp](https://github.com/freeswitch/spandsp) - mod_spandsp 背后的 DSP 库，负责传真、音调检测和回声消除。 `C`
- [eslgo](https://github.com/percipia/eslgo) - Go 语言的 Event Socket 客户端，支持 inbound 和 outbound 两种模式，事件带类型。 `MPL-2.0` `Go`
- [freeswitch-esl-node](https://github.com/ictinnovations/freeswitch-esl-node) - Node.js 的 Event Socket 客户端，带 TypeScript 类型定义，无第三方依赖。 `MIT` `TypeScript`

## 工具

- [freeswitch-tools](https://github.com/rts-cn/freeswitch-tools) - FreeSWITCH 的各类辅助工具。 `MPL-2.0` `C`
- [sipexer](https://github.com/miconda/sipexer) - 现代、灵活的 SIP/VoIP 命令行工具。 `GPL-3.0` `Go`
- [SIPp](https://github.com/SIPp/sipp) - SIP 协议测试工具。 `C++`
- [sngrep](https://github.com/irontec/sngrep) - 终端里的 SIP 抓包工具，能画出呼叫流程图，排查问题最快的办法之一。 `C`
- [HOMER](https://github.com/sipcapture/homer) - 跨多台服务器的 SIP 抓包与关联分析，可以把一通电话经过的每一跳串起来看。 `Go`
- [freeswitch_exporter](https://github.com/florentchauveau/freeswitch_exporter) - 通过 Event Socket 读取 FreeSWITCH 数据的 Prometheus exporter，用于监控面板和告警。 `MIT` `Go`
- [SIPVicious](https://github.com/EnableSecurity/sipvicious) - SIP 安全审计工具集，最好先拿自己的服务器测一遍。 `Python`
- [sippts](https://github.com/Pepelux/sippts) - 用于扫描、枚举和测试 SIP 服务的工具集。 `GPL-3.0` `Python`
- [solidping](https://github.com/fclairamb/solidping) - Go 编写的自托管可用性监控工具。SIP 检查通过 UDP/TCP/TLS 向 FreeSWITCH 发送 OPTIONS（或尝试 REGISTER），无响应时告警。 `AGPL-3.0` `Go`
- [cascade-realtime-gateway](https://github.com/rasonyang/cascade-realtime-gateway) - Go 编写的 OpenAI Realtime 协议网关，在网关背后串联运行 ASR + LLM + TTS，让 Realtime 客户端可以混用 Deepgram、OpenAI 和 Qwen。只支持 24 kHz PCM。 `Apache-2.0` `Go`
- [ai-native-callcenter](https://github.com/rasonyang/ai-native-callcenter) - FreeSWITCH 上的 AI 优先呼叫中心：实时语音模型先接听，需要真人时转入 mod_callcenter 队列，对话文本随来电一并交给坐席。单个 Go 二进制文件，外加 PostgreSQL。 `Apache-2.0` `Go`
- [sipmon](https://github.com/miuda-ai/sipmon) - Rust 编写的被动式 SIP/RTP 信令与媒体质量监控工具。部署在镜像口，或离线分析 pcap 即可，不依赖 PBX：按 Call-ID 关联呼叫，提供 RFC 3550 抖动/丢包与 RTCP RTT 统计、E-model MOS、TURN 识别和 20+ 条诊断规则，实时 TUI 展示并可导出 JSONL。 `Rust`
- [ICTFax](https://github.com/ictinnovations/ictfax) - 基于 FreeSWITCH 和 mod_spandsp 的传真服务器，支持 T.38，带 Web 界面和 REST API。 `GPL-3.0`
- [ICTCore](https://github.com/ictinnovations/ictcore) - 把 FreeSWITCH 的语音、传真和消息能力封装成 REST API 的框架，呼叫流程可编程。 `MPL-2.0` `PHP`
- [ICTPBX Community Edition](https://github.com/ictinnovations/ictpbx-community-edition) - 打包了 FreeSWITCH 和 FusionPBX 的多租户 PBX，提供 REST API。 `MPL-2.0` `PHP`
- [PBX-MCP](https://github.com/ictinnovations/pbx-mcp) - MCP 服务器，让 AI 助手通过 Event Socket 查询运行中的 FreeSWITCH：通道、注册和呼叫。 `TypeScript`

## 资源

- [FreeSWITCH 中文语音包](https://github.com/rts-cn/zh) - FreeSWITCH 的中文语音提示音。 `MPL-2.0`
- [fsdg-code](https://github.com/rts-cn/fsdg-code) - 《FreeSWITCH 权威指南》随书代码。
- [SIP Resources](https://github.com/miconda/sip-resources) - 各种 SIP 资源。 `GPL-2.0`

## 客户端

- [我用过的那些 SIP 客户端](http://rts.cn/blog/sip/) - 作者实际用过的 SIP 客户端与使用感受。
- [XSwitch Apps](https://xswitch.cn/app/) - 适用于 Android、iOS、macOS、Windows 和 HarmonyOS 的 CherryCall SIP 客户端与 VibCall WebRTC 客户端。
- [SaraPhone](https://github.com/gmaruzz/saraphone) - WebRTC SIP 电话。 `MPL-2.0` `JavaScript`
- [JsSIP](https://github.com/versatica/JsSIP) - JavaScript 的 SIP over WebSocket 库，可以对接 mod_sofia 构建浏览器电话。 `JavaScript`
- [SIP.js](https://github.com/onsip/SIP.js) - 另一个常用的 JavaScript SIP 库，常见场景下接口更简单。 `MIT` `TypeScript`
- [baresip](https://github.com/baresip/baresip) - 模块化的 SIP 用户代理，适合做可编程的测试终端。 `BSD-3-Clause` `C`
- [web-sip-phone](https://github.com/rasonyang/web-sip-phone) - Chrome 扩展，在 offscreen document 中维持 SIP over WebSocket 注册，页面刷新也不会中断通话。它自己没有拨号盘：接听、保持由 FreeSWITCH 通过 uuid_phone_event 驱动。 `TypeScript`

## 朋友们

FreeSWITCH 的朋友们

- [awesome-hep](https://github.com/sipcapture/awesome-hep) - 支持 HEP/EEP 的项目清单。 `MIT`
- [Kamailio](https://github.com/kamailio/kamailio) - SIP 代理服务器。 `C`
- [OpenSIPS](https://github.com/OpenSIPS/opensips) - SIP 代理服务器。
- [FusionPBX](https://github.com/fusionpbx/fusionpbx) - 很多人在 FreeSWITCH 上使用的多租户 Web 管理界面。 `PHP`
- [jambonz-feature-server](https://github.com/jambonz/jambonz-feature-server) - 开源 CPaaS：drachtio 处理 SIP，FreeSWITCH 处理媒体，提供 Webhook 和 WebSocket API。 `MIT` `JavaScript`
- [drachtio-server](https://github.com/drachtio/drachtio-server) - 用 Node.js 控制的 SIP 服务器，也是 jambonz 的信令部分。 `C++`
- [BigBlueButton](https://github.com/bigbluebutton/bigbluebutton) - 面向教学的网络会议系统，音频混音跑在 FreeSWITCH 上。 `LGPL-3.0`
- [rtpengine](https://github.com/sipwise/rtpengine) - RTP 代理和媒体中继，处理 NAT 穿越、录音和转码。 `GPL-3.0`
- [coturn](https://github.com/coturn/coturn) - 大多数 WebRTC 部署都会用到的 STUN/TURN 服务器。 `C`
- [FreeSBC](https://github.com/rasonyang/freesbc) - Go 编写的 SBC，置于 FreeSWITCH 前端：SIP 走 UDP/WS/WSS，RTP 在进程内转发，支持 SDES-SRTP 与 WebRTC（ICE-Lite、DTLS-SRTP），只用一个 YAML 文件配置。 `Apache-2.0` `Go`
- [RustPBX](https://github.com/restsend/rustpbx) - Rust 编写的软件定义 PBX：完整 SIP 栈（UDP/TCP/WS/TLS/WebRTC）、RTP 转发与转码、Webhook 路由 + WebSocket 实时呼叫控制（RWI）、可将 AI 语音智能体作为通话参与者、内置 Web 控制台。无需 C 模块，无需重新编译。 `MIT` `Rust`
- [RSIPStack](https://github.com/restsend/rsipstack) - Rust 编写的 SIP 协议栈，符合 RFC 3261/3262：支持 UDP/TCP/TLS/WebSocket 传输、事务层与对话层、摘要认证、PRACK。可用于构建 SIP 代理、注册服务器、用户代理或 WebRTC SBC，还能在基于 embassy 的嵌入式目标上以 no_std 运行。 `MIT` `Rust`
- [RustRTC](https://github.com/restsend/rustrtc) - Rust 高性能实时通信库：以统一的 PeerConnection API 提供 WebRTC、RTP/SRTP 与 T.38 传真，完整的 ICE/STUN/TURN 支持，以及 UPnP NAT 穿越。基准测试吞吐量约为 webrtc-rs 的 3.3 倍。 `MIT` `Rust`
- [CGRates](https://github.com/cgrates/cgrates) - 面向电信的实时计费与出账系统。 `AGPL-3.0` `Go`
- [Janus](https://janus.conf.meetecho.com/) - WebRTC 网关与媒体服务器。
- [mediasoup](https://mediasoup.org/) - WebRTC SFU 媒体服务器。

## 其它

- [awesome-webrtc](https://github.com/cameronroe/awesome-webrtc) - WebRTC 模块与资源清单。 `CC0-1.0`
- [awesome-rtc](https://github.com/rtckit/awesome-rtc) - 实时通信资源清单。 `CC0-1.0`
- [awesome](https://github.com/sindresorhus/awesome) - 各类精选清单的合集。 `CC0-1.0`
- [react-native-webrtc](https://github.com/react-native-webrtc/react-native-webrtc) - 为 React Native 应用提供 WebRTC 支持。 `MIT`
- [webrtc-build](https://github.com/shiguredo-webrtc-build/webrtc-build) - WebRTC 的构建脚本与预编译产物。

FreeSWITCH-CN 微信公众号

![FreeSWITCH-CN 微信公众号](img/qrcode_for_FreeSWITCH-CN-wechat.jpg)

## 过时

保留作参考：以下链接已失效、已归档或不再维护。

- [GitMemory](https://www.gitmemory.com/signalwire/freeswitch) - FreeSWITCH 的 GitMemory 页面，该服务已关闭。
- [WebRTC.work](https://webrtcwork.com/) - 致力于让 WebRTC 更易用的网站，域名已无法解析。
- [SimpleDemo-jQueryVertoJS](https://github.com/Mazuh/SimpleDemo-jQueryVertoJS) - 简单的 jQuery Verto 视频会议示例，作者已归档。

## 投稿

欢迎投稿，收录标准、条目格式和标签规则见 [CONTRIBUTING.zh-CN.md](CONTRIBUTING.zh-CN.md)。感谢所有 [contributors](https://github.com/rts-cn/awesome-freeswitch/graphs/contributors) 的贡献。

## 许可证

[CC0 1.0 Universal](LICENSE)

## 星标历史

[![Star History Chart](https://api.star-history.com/chart?repos=rts-cn/awesome-freeswitch&type=date&legend=top-left)](https://www.star-history.com/?repos=rts-cn%2Fawesome-freeswitch&type=date&legend=top-left)
