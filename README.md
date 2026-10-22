# Awesome FreeSWITCH

A curated list of awesome FreeSWITCH resources, modules, frameworks, libraries and software. Inspired by [awesome-go](https://github.com/avelino/awesome-go).

## Contributing

We support multiple languages, each language on one line. Please make a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) to keep us Awesome.

We don't have a complete contributing guide yet, maybe take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/rts-cn/awesome-freeswitch/graphs/contributors); you rock!

*If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

我们支持多语言，每个语言占一行，欢迎提PR。

## Contents | 内容

- [Useful Links 有用的链接](#useful-links--有用的链接)
- [Modules 模块](#modules--模块)
- [Libs 库](#libs--库)
- [Tools 工具](#tools--工具)
- [Resources 资源](#resources--资源)
- [Clients 客户端](#clients--客户端)
- [Friends 朋友们](#friends--朋友们)
- [Others 其它](#others--其它)
- [Out-dated 过时](#out-dated--过时)

## Useful Links | 有用的链接

* https://freeswitch.org - The FreeSWITCH Community.
* https://freeswitch.org - FreeSWITCH社区。
* https://cluecon.com - ClueCon is an annual telephony and Voice over IP developers conference started in 2005 by the FreeSWITCH core developer team
* https://rts.cn/events/ RTSCon is an anual telephony and VoIP developers conference started in 2012 by the FreeSWITCH.org.cn maintainers. Formerly known as FreeSWITCH Developers' Salon.
* https://rts.cn/events/ RTSCon 是一个年度会议，由FreeSWITCH中文社区发起（2012），以前叫FreeSWITCH开发者沙龙，2020年改为此名。
* https://github.com/signalwire/freeswitch/releases/ FreeSWITCH Release Notes
* https://developer.signalwire.com/freeswitch - FreeSWITCH documentation, including the module reference and the Event Socket protocol.
* https://developer.signalwire.com/freeswitch - FreeSWITCH 官方文档，包括模块参考和 Event Socket 协议说明。
* https://github.com/signalwire/freeswitch-docs - Source of that documentation, so fixes can go in as pull requests.
* https://github.com/signalwire/freeswitch-docs - 上述文档的源码，发现错误可以直接提 PR。
* https://signalwire.com - An elastic communications cloud with advanced APIs for voice, SMS
and video designed by the pioneers of software-defined telecom.
* https://signalwire.com - 用于音频、视频、SMS的高级云计算通信平台，由软件定义电信网先驱们设计。
* https://forum.signalwire.community/ - FreeSWITCH SignalWire Community Forum
* https://forum.signalwire.community/ - FreeSWITCH SignalWire官方社区论坛
* http://www.freeswitch.org.cn - FreeSWITCH中文社区。
* https://www.kamailio.org.cn - Kamailio中文社区。
* http://rts.cn - RTS实时解决方案社区，包含FreeSWITCH和Kamailio、OpenSIPS、WebRTC、AI等，探讨开源与商业解决方案的完美结合。
* https://book.dujinfang.com/ FreeSWITCH相关中文图书。
* http://x-y-t.cn/training.html FreeSWITCH培训课程（中文）。
* https://github.com/rts-cn RTS实时通信解决方案。
* https://github.com/freeswitch 一些外围FreeSWITCH模块。
* https://github.com/rts-cn/xswitch-free [XSwitch.cn](https://xswitch.cn)提供的Docker镜像，仅供学习用途。
* https://github.com/rts-cn/xswitch-free FreeSWITCH Docker Image by [XSwitch.cn](https://xswitch.cn)，Useful for learning FreeSWITCH.

## Modules | 模块

* https://github.com/rts-cn/mod_shine - 使用shine进行MP3录音的库。
* https://github.com/rts-cn/mod_vnc - 与VNC交互的模块
* https://github.com/rts-cn/mod_x11 - 与X11交互的模块
* https://github.com/rts-cn/mod_aac - AAC编解码模块
* https://github.com/freeswitch/mod_unimrcp - 通过MRCP协议连接ASR/TTS的模块。
* https://github.com/freeswitch/mod_mosquitto FreeSWITCH interface to an MQTT broker using the Eclipse Mosquitto project C client library.
* https://github.com/freeswitch/mod_coreclr The future home of a new Core .NET 3.1 based language plugin module.
* https://github.com/seven1240/mod_v FreeSWITCH module in V.
* https://github.com/amigniter/mod_audio_stream - Streams a channel's audio to a WebSocket and plays returned audio back. The usual bridge between FreeSWITCH and a speech or AI service.
* https://github.com/amigniter/mod_audio_stream - 把通道音频推送到 WebSocket，并播放返回的音频，常用来连接 FreeSWITCH 和语音识别或 AI 服务。

## Libs | 库

* https://github.com/EvoluxBR/greenswitch Battle proven FreeSWITCH Event Socket Protocol client implementation with Gevent
* https://github.com/space88man/trioswitch FreeSWITCH Event Socket Protocol client implementation with Trio (based on GreenSWITCH)
* https://github.com/freeswitch/sofia-sip - The SIP stack FreeSWITCH is built on, now maintained by the FreeSWITCH project.
* https://github.com/freeswitch/sofia-sip - FreeSWITCH 所用的 SIP 协议栈，现由 FreeSWITCH 项目维护。
* https://github.com/freeswitch/spandsp - DSP library behind mod_spandsp: fax, tone detection and echo cancellation.
* https://github.com/freeswitch/spandsp - mod_spandsp 背后的 DSP 库，负责传真、音调检测和回声消除。
* https://github.com/percipia/eslgo - Event Socket client for Go, inbound and outbound modes, typed events.
* https://github.com/percipia/eslgo - Go 语言的 Event Socket 客户端，支持 inbound 和 outbound 两种模式。
* https://github.com/ictinnovations/freeswitch-esl-node - Event Socket client for Node.js with TypeScript types and no dependencies.
* https://github.com/ictinnovations/freeswitch-esl-node - Node.js 的 Event Socket 客户端，带 TypeScript 类型定义，无第三方依赖。


## Tools | 工具

* https://github.com/rts-cn/freeswitch-tools - FreeSWITCH Tools
* https://github.com/miconda/sipexer SIP命令行工具
* https://github.com/SIPp/sipp a SIP protocol test tool SIP压测工具
* https://github.com/irontec/sngrep - SIP capture in the terminal with call flow diagrams. The quickest way to see what a box is doing.
* https://github.com/irontec/sngrep - 终端里的 SIP 抓包工具，能画出呼叫流程图，排查问题最快的办法之一。
* https://github.com/sipcapture/homer - SIP capture and correlation across many servers, so one call can be followed across every hop.
* https://github.com/sipcapture/homer - 跨多台服务器的 SIP 抓包与关联分析，可以把一通电话经过的每一跳串起来看。
* https://github.com/florentchauveau/freeswitch_exporter - Prometheus exporter that reads FreeSWITCH over the Event Socket, for dashboards and alerts.
* https://github.com/florentchauveau/freeswitch_exporter - 通过 Event Socket 读取 FreeSWITCH 数据的 Prometheus exporter，用于监控面板和告警。
* https://github.com/EnableSecurity/sipvicious - Tools for auditing SIP systems. Run it against your own server before someone else does.
* https://github.com/EnableSecurity/sipvicious - SIP 安全审计工具集，最好先拿自己的服务器测一遍。
* https://github.com/Pepelux/sippts - Toolkit for scanning, enumerating and testing SIP services.
* https://github.com/Pepelux/sippts - 用于扫描、枚举和测试 SIP 服务的工具集。
* https://github.com/fclairamb/solidping - Self-hosted uptime monitoring in Go. Its SIP check sends OPTIONS (or tries a REGISTER) to FreeSWITCH over UDP, TCP or TLS and alerts when it stops answering.
* https://github.com/rasonyang/cascade-realtime-gateway - OpenAI Realtime protocol gateway in Go, running a cascaded ASR + LLM + TTS behind the wire, so a Realtime client can mix Deepgram, OpenAI and Qwen. 24 kHz PCM only.
* https://github.com/rasonyang/cascade-realtime-gateway - Go 编写的 OpenAI Realtime 协议网关，协议后面接的是 ASR + LLM + TTS 级联，可以混用 Deepgram、OpenAI、Qwen。只支持 24 kHz PCM。
* https://github.com/rasonyang/ai-native-callcenter - AI-first call center on FreeSWITCH: a realtime voice model answers the call, then transfers into mod_callcenter queues with the transcript following the caller. One Go binary plus PostgreSQL.
* https://github.com/rasonyang/ai-native-callcenter - FreeSWITCH 上的 AI 优先呼叫中心：实时语音模型先接听，需要真人时转入 mod_callcenter 队列，对话文本跟着来电一起交到坐席。一个 Go 二进制加 PostgreSQL。
* https://github.com/miuda-ai/sipmon - Passive SIP/RTP monitoring tool in Rust. Runs on a mirror port or offline pcap, no PBX dependency: Call-ID call correlation, RFC3550 jitter/loss, RTCP RTT, E-model MOS, TURN detection, 20+ diagnostic rules, live TUI and JSONL export.
* https://github.com/miuda-ai/sipmon - Rust 编写的被动式 SIP/RTP 信令与媒体质量监控工具。部署在镜像口或离线分析 pcap 即可，不依赖 PBX：按 Call-ID 关联呼叫、RFC3550 抖动/丢包、RTCP RTT、E-model MOS、TURN 识别、20+ 条诊断规则，实时 TUI 展示并可导出 JSONL。
* https://github.com/ictinnovations/ictfax - Fax server on FreeSWITCH and mod_spandsp, with T.38, a web interface and a REST API.
* https://github.com/ictinnovations/ictfax - 基于 FreeSWITCH 和 mod_spandsp 的传真服务器，支持 T.38，带 Web 界面和 REST API。
* https://github.com/ictinnovations/ictcore - Framework that exposes FreeSWITCH voice, fax and messaging as a REST API with programmable call flows.
* https://github.com/ictinnovations/ictcore - 把 FreeSWITCH 的语音、传真和消息能力封装成 REST API 的框架，呼叫流程可编程。
* https://github.com/ictinnovations/ictpbx-community-edition - Multi-tenant PBX packaging FreeSWITCH and FusionPBX with a REST API.
* https://github.com/ictinnovations/ictpbx-community-edition - 打包了 FreeSWITCH 和 FusionPBX 的多租户 PBX，提供 REST API。
* https://github.com/ictinnovations/pbx-mcp - MCP server that lets an AI assistant query a live FreeSWITCH over the Event Socket: channels, registrations and calls.
* https://github.com/ictinnovations/pbx-mcp - MCP 服务器，让 AI 助手通过 Event Socket 查询运行中的 FreeSWITCH：通道、注册和呼叫。

## Resources | 资源

* https://github.com/rts-cn/zh FreeSWITCH中文语音包
* https://github.com/rts-cn/fsdg-code 《FreeSWITCH权威指南》随书代码。
* https://github.com/miconda/sip-resources SIP Resources SIP资源

## Clients | 客户端

* [我用过的那些SIP客户端](http://rts.cn/blog/sip/)
* https://xswitch.cn/app/ CherryCall SIP Clients and VibCall WebRTC based clients for Android, iOS, macOS, Windows and HarmonyOS.
* https://github.com/gmaruzz/saraphone WebRTC SIP Phone
* https://github.com/versatica/JsSIP - JavaScript SIP over WebSocket library for building browser phones against mod_sofia.
* https://github.com/versatica/JsSIP - JavaScript 的 SIP over WebSocket 库，可以对接 mod_sofia 做浏览器电话。
* https://github.com/onsip/SIP.js - The other common JavaScript SIP library, with a simpler API for everyday cases.
* https://github.com/onsip/SIP.js - 另一个常用的 JavaScript SIP 库，常见场景下接口更简单。
* https://github.com/baresip/baresip - Modular SIP user agent, handy as a scriptable test endpoint.
* https://github.com/baresip/baresip - 模块化的 SIP 用户代理，适合做可编程的测试终端。
* https://github.com/rasonyang/web-sip-phone - Chrome extension holding a SIP over WebSocket registration in an offscreen document, so a call survives page reloads. No dialpad: FreeSWITCH drives it over uuid_phone_event.
* https://github.com/rasonyang/web-sip-phone - Chrome 扩展，在 offscreen document 里持有 SIP over WebSocket 注册，页面刷新不会断话。它自己没有拨号盘：接听、保持由 FreeSWITCH 通过 uuid_phone_event 驱动。

## Friends | 朋友们

Friends of FreeSWITCH | FreeSWITCH的朋友们

* https://github.com/sipcapture/awesome-hep AweSome Friend
* https://github.com/kamailio/kamailio SIP Proxy
* https://github.com/OpenSIPS/opensips SIP Proxy
* https://github.com/fusionpbx/fusionpbx - Multi-tenant web interface that many people run on top of FreeSWITCH.
* https://github.com/fusionpbx/fusionpbx - 很多人在 FreeSWITCH 上使用的多租户 Web 管理界面。
* https://github.com/jambonz/jambonz-feature-server - Open source CPaaS: drachtio for SIP, FreeSWITCH for media, webhook and WebSocket APIs.
* https://github.com/jambonz/jambonz-feature-server - 开源 CPaaS：drachtio 处理 SIP，FreeSWITCH 处理媒体，提供 webhook 和 WebSocket API。
* https://github.com/drachtio/drachtio-server - SIP server controlled from Node.js, the signalling half of jambonz.
* https://github.com/drachtio/drachtio-server - 用 Node.js 控制的 SIP 服务器，也是 jambonz 的信令部分。
* https://github.com/bigbluebutton/bigbluebutton - Web conferencing for teaching. Its audio mixing runs on FreeSWITCH.
* https://github.com/bigbluebutton/bigbluebutton - 面向教学的网络会议系统，音频混音跑在 FreeSWITCH 上。
* https://github.com/sipwise/rtpengine - RTP proxy and media relay for NAT traversal, recording and transcoding.
* https://github.com/sipwise/rtpengine - RTP 代理和媒体中继，处理 NAT 穿越、录音和转码。
* https://github.com/coturn/coturn - The STUN and TURN server most WebRTC deployments end up running.
* https://github.com/coturn/coturn - 大多数 WebRTC 部署都会用到的 STUN/TURN 服务器。
* https://github.com/rasonyang/freesbc - SBC in Go, sits in front of FreeSWITCH: SIP over UDP/WS/WSS, in-process RTP relay, SDES-SRTP and WebRTC (ICE-Lite, DTLS-SRTP), configured from one YAML file.
* https://github.com/rasonyang/freesbc - Go 编写的 SBC，放在 FreeSWITCH 前面：SIP 走 UDP/WS/WSS，RTP 在进程内转发，支持 SDES-SRTP 与 WebRTC（ICE-Lite、DTLS-SRTP），只用一个 YAML 文件配置。
* https://github.com/restsend/rustpbx - Software-defined PBX in Rust: full SIP stack (UDP/TCP/WS/TLS/WebRTC), RTP relay and transcoding, webhook routing plus WebSocket real-time call control (RWI), AI voice agents as call participants, built-in Web console. No C modules, no recompilation.
* https://github.com/restsend/rustpbx - Rust 编写的软件定义 PBX：完整 SIP 栈（UDP/TCP/WS/TLS/WebRTC）、RTP 转发与转码、Webhook 路由 + WebSocket 实时呼叫控制（RWI）、AI 语音智能体可作为通话参与者、内置 Web 控制台。无需 C 模块，无需重新编译。
* https://github.com/restsend/rsipstack - RFC 3261/3262 compliant SIP stack in Rust: UDP/TCP/TLS/WebSocket transports, transaction and dialog layers, digest auth, PRACK. Build SIP proxies, registrars, user agents or WebRTC SBCs; also runs no_std on embassy-based embedded targets.
* https://github.com/restsend/rsipstack - Rust 编写的 SIP 协议栈，符合 RFC 3261/3262：支持 UDP/TCP/TLS/WebSocket 传输、事务层与对话层、摘要认证、PRACK。可用于构建 SIP 代理、注册服务器、用户代理或 WebRTC SBC，还支持 no_std 跑在 embassy 嵌入式环境。
* https://github.com/restsend/rustrtc - High-performance real-time communication library in Rust: WebRTC, RTP/SRTP and T.38 fax behind a unified PeerConnection API, full ICE/STUN/TURN, UPnP NAT traversal. Benchmarked at ~3.3x the throughput of webrtc-rs.
* https://github.com/restsend/rustrtc - Rust 高性能实时通信库：以统一的 PeerConnection API 提供 WebRTC、RTP/SRTP 与 T.38 传真，完整 ICE/STUN/TURN 与 UPnP NAT 穿越。基准测试吞吐量约为 webrtc-rs 的 3.3 倍。
* https://github.com/cgrates/cgrates Billing
* https://janus.conf.meetecho.com/ Janus
* https://mediasoup.org/ WebRTC

## Others | 其它

* https://github.com/cameronroe/awesome-webrtc
* https://github.com/rtckit/awesome-rtc AweSome RTC
* https://github.com/sindresorhus/awesome Interesting AweSome Stuff
* https://github.com/react-native-webrtc/react-native-webrtc React Native WebRTC
* https://github.com/shiguredo-webrtc-build/webrtc-build WebRTC Build

FreeSWITCH-CN Wechat Official Accounts | FreeSWITCH微信公众号

![FreeSWITCH-CN微信公众号](img/qrcode_for_FreeSWITCH-CN-wechat.jpg)

## Out-dated | 过时

Kept for reference. These links are dead, archived or no longer maintained.

保留作参考：以下链接已失效、已归档或不再维护。

* https://www.gitmemory.com/signalwire/freeswitch Git Memory of FreeSWITCH. GitMemory has shut down.
* https://www.gitmemory.com/signalwire/freeswitch FreeSWITCH 的 Git Memory 页面，GitMemory 服务已关闭。
* https://webrtcwork.com/ A space dedicated to making WebRTC work easier. The domain no longer resolves.
* https://webrtcwork.com/ 致力于让 WebRTC 更易用的网站，域名已无法解析。
* https://github.com/Mazuh/SimpleDemo-jQueryVertoJS Simple jQuery Verto video conference demo. Archived by its author.
* https://github.com/Mazuh/SimpleDemo-jQueryVertoJS 简单的 jQuery Verto 视频会议示例，作者已归档。

## Star History

[![Star History Chart](https://api.star-history.com/chart?repos=rts-cn/awesome-freeswitch&type=date&legend=top-left)](https://www.star-history.com/?repos=rts-cn%2Fawesome-freeswitch&type=date&legend=top-left)
