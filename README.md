# Awesome FreeSWITCH

English | [简体中文](README.zh-CN.md)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Stars](https://img.shields.io/github/stars/rts-cn/awesome-freeswitch?style=flat-square&logo=github)](https://github.com/rts-cn/awesome-freeswitch/stargazers)

A curated list of awesome FreeSWITCH resources, modules, frameworks, libraries and software. Inspired by [awesome-go](https://github.com/avelino/awesome-go).

**Scope**: FreeSWITCH-related projects you can use today. Descriptions are based on each project's own wording, lightly edited. For the API reference, use the [official docs](https://developer.signalwire.com/freeswitch).

## Contents

- [Useful Links](#useful-links)
- [Modules](#modules)
- [Libs](#libs)
- [Tools](#tools)
- [Resources](#resources)
- [Clients](#clients)
- [Friends](#friends)
- [Others](#others)
- [Out-dated](#out-dated)

## Useful Links

- [FreeSWITCH](https://freeswitch.org) - The FreeSWITCH Community.
- [ClueCon](https://cluecon.com) - ClueCon is an annual telephony and VoIP developers conference started in 2005 by the FreeSWITCH core developer team.
- [RTSCon](https://rts.cn/events/) - RTSCon is an annual telephony and VoIP developers conference started in 2012 by the FreeSWITCH.org.cn maintainers. Formerly known as FreeSWITCH Developers' Salon; renamed in 2020.
- [FreeSWITCH Releases](https://github.com/signalwire/freeswitch/releases/) - FreeSWITCH Release Notes.
- [FreeSWITCH Docs](https://developer.signalwire.com/freeswitch) - FreeSWITCH documentation, including the module reference and the Event Socket protocol.
- [freeswitch-docs](https://github.com/signalwire/freeswitch-docs) - Source of that documentation, so fixes can go in as pull requests. `MIT`
- [SignalWire](https://signalwire.com) - An elastic communications cloud with advanced APIs for voice, SMS and video designed by the pioneers of software-defined telecom.
- [SignalWire Community](https://forum.signalwire.community/) - FreeSWITCH SignalWire Community Forum.
- [FreeSWITCH Chinese community](http://www.freeswitch.org.cn) - The Chinese FreeSWITCH community.
- [Kamailio Chinese community](https://www.kamailio.org.cn) - The Chinese Kamailio community.
- [RTS](http://rts.cn) - A realtime solutions community covering FreeSWITCH, Kamailio, OpenSIPS, WebRTC and AI.
- [FreeSWITCH books](https://book.dujinfang.com/) - FreeSWITCH books in Chinese.
- [FreeSWITCH training](http://x-y-t.cn/training.html) - FreeSWITCH training courses in Chinese.
- [RTS (GitHub)](https://github.com/rts-cn) - Realtime communication solutions.
- [FreeSWITCH (GitHub)](https://github.com/freeswitch) - Some peripheral FreeSWITCH modules.
- [XSwitch Free](https://github.com/rts-cn/xswitch-free) - FreeSWITCH Docker image by [XSwitch.cn](https://xswitch.cn). Useful for learning FreeSWITCH.

## Modules

- [mod_shine](https://github.com/rts-cn/mod_shine) - FreeSWITCH module for MP3 recording using shine.
- [mod_vnc](https://github.com/rts-cn/mod_vnc) - FreeSWITCH module to interact with VNC. `C`
- [mod_x11](https://github.com/rts-cn/mod_x11) - FreeSWITCH module to interact with the X11 desktop. `C`
- [mod_aac](https://github.com/rts-cn/mod_aac) - AAC codec module for FreeSWITCH. `C`
- [mod_unimrcp](https://github.com/freeswitch/mod_unimrcp) - Module that connects ASR/TTS over the MRCP protocol. `C`
- [mod_mosquitto](https://github.com/freeswitch/mod_mosquitto) - FreeSWITCH interface to an MQTT broker using the Eclipse Mosquitto project C client library. `C`
- [mod_coreclr](https://github.com/freeswitch/mod_coreclr) - The future home of a new .NET Core 3.1-based language plugin module. `MIT` `C#`
- [mod_v](https://github.com/seven1240/mod_v) - FreeSWITCH module in V. `V`
- [mod_audio_stream](https://github.com/amigniter/mod_audio_stream) - Production-grade WebSocket audio streaming for FreeSWITCH. Streams a channel's audio to a WebSocket and plays the returned audio back. The usual bridge between FreeSWITCH and a speech or AI service. `C++`

## Libs

- [GreenSWITCH](https://github.com/EvoluxBR/greenswitch) - Battle-proven FreeSWITCH Event Socket Protocol client implementation with Gevent. `Python`
- [TrioSWITCH](https://github.com/space88man/trioswitch) - FreeSWITCH Event Socket Protocol client implementation with Trio (based on GreenSWITCH).
- [sofia-sip](https://github.com/freeswitch/sofia-sip) - The SIP stack FreeSWITCH is built on, now maintained by the FreeSWITCH project. `LGPL-2.1` `C`
- [spandsp](https://github.com/freeswitch/spandsp) - DSP library behind mod_spandsp: fax, tone detection and echo cancellation. `C`
- [eslgo](https://github.com/percipia/eslgo) - Event Socket client for Go, inbound and outbound modes, typed events. `MPL-2.0` `Go`
- [freeswitch-esl-node](https://github.com/ictinnovations/freeswitch-esl-node) - Event Socket client for Node.js with TypeScript types and no dependencies. `MIT` `TypeScript`

## Tools

- [freeswitch-tools](https://github.com/rts-cn/freeswitch-tools) - Assorted FreeSWITCH helper tools. `MPL-2.0` `C`
- [sipexer](https://github.com/miconda/sipexer) - Modern and flexible SIP/VoIP command-line tool. `GPL-3.0` `Go`
- [SIPp](https://github.com/SIPp/sipp) - SIP protocol test tool. `C++`
- [sngrep](https://github.com/irontec/sngrep) - SIP capture in the terminal with call flow diagrams. The quickest way to see what a box is doing. `C`
- [HOMER](https://github.com/sipcapture/homer) - SIP capture and correlation across many servers, so a single call can be followed through every hop. `Go`
- [freeswitch_exporter](https://github.com/florentchauveau/freeswitch_exporter) - Prometheus exporter that reads FreeSWITCH over the Event Socket, for dashboards and alerts. `MIT` `Go`
- [SIPVicious](https://github.com/EnableSecurity/sipvicious) - Tools for auditing SIP systems. Run it against your own server before someone else does. `Python`
- [sippts](https://github.com/Pepelux/sippts) - Toolkit for scanning, enumerating and testing SIP services. `GPL-3.0` `Python`
- [solidping](https://github.com/fclairamb/solidping) - Self-hosted uptime monitoring in Go. Its SIP check sends OPTIONS (or tries a REGISTER) to FreeSWITCH over UDP, TCP or TLS and alerts when it stops answering. `AGPL-3.0` `Go`
- [cascade-realtime-gateway](https://github.com/rasonyang/cascade-realtime-gateway) - OpenAI Realtime protocol gateway in Go, running a cascaded ASR + LLM + TTS behind the wire, so a Realtime client can mix Deepgram, OpenAI and Qwen. 24 kHz PCM only. `Apache-2.0` `Go`
- [ai-native-callcenter](https://github.com/rasonyang/ai-native-callcenter) - AI-first call center on FreeSWITCH: a real-time voice model answers the call, then transfers into mod_callcenter queues with the transcript following the caller. One Go binary plus PostgreSQL. `Apache-2.0` `Go`
- [sipmon](https://github.com/miuda-ai/sipmon) - Passive SIP/RTP monitoring tool in Rust. Runs on a mirror port or on offline pcap files, with no PBX dependency: Call-ID call correlation, RFC 3550 jitter/loss, RTCP RTT, E-model MOS, TURN detection, 20+ diagnostic rules, live TUI and JSONL export. `Rust`
- [ICTFax](https://github.com/ictinnovations/ictfax) - Fax server on FreeSWITCH and mod_spandsp, with T.38, a web interface and a REST API. `GPL-3.0`
- [ICTCore](https://github.com/ictinnovations/ictcore) - Framework that exposes FreeSWITCH voice, fax and messaging as a REST API with programmable call flows. `MPL-2.0` `PHP`
- [ICTPBX Community Edition](https://github.com/ictinnovations/ictpbx-community-edition) - Multi-tenant PBX packaging FreeSWITCH and FusionPBX with a REST API. `MPL-2.0` `PHP`
- [PBX-MCP](https://github.com/ictinnovations/pbx-mcp) - MCP server that lets an AI assistant query a live FreeSWITCH over the Event Socket: channels, registrations and calls. `TypeScript`

## Resources

- [FreeSWITCH Chinese voice prompts](https://github.com/rts-cn/zh) - Chinese voice prompts for FreeSWITCH. `MPL-2.0`
- [fsdg-code](https://github.com/rts-cn/fsdg-code) - Sample code from the book 《FreeSWITCH 权威指南》.
- [SIP Resources](https://github.com/miconda/sip-resources) - Various SIP resources. `GPL-2.0`

## Clients

- [SIP clients I have used](http://rts.cn/blog/sip/) - Notes on the SIP clients the author has personally used.
- [XSwitch Apps](https://xswitch.cn/app/) - CherryCall SIP and VibCall WebRTC-based clients for Android, iOS, macOS, Windows and HarmonyOS.
- [SaraPhone](https://github.com/gmaruzz/saraphone) - WebRTC SIP phone. `MPL-2.0` `JavaScript`
- [JsSIP](https://github.com/versatica/JsSIP) - JavaScript SIP over WebSocket library for building browser phones against mod_sofia. `JavaScript`
- [SIP.js](https://github.com/onsip/SIP.js) - The other common JavaScript SIP library, with a simpler API for everyday cases. `MIT` `TypeScript`
- [baresip](https://github.com/baresip/baresip) - Modular SIP user agent, handy as a scriptable test endpoint. `BSD-3-Clause` `C`
- [web-sip-phone](https://github.com/rasonyang/web-sip-phone) - Chrome extension keeping a SIP-over-WebSocket registration alive in an offscreen document, so a call survives page reloads. No dialpad: FreeSWITCH drives it over uuid_phone_event. `TypeScript`

## Friends

Friends of FreeSWITCH

- [awesome-hep](https://github.com/sipcapture/awesome-hep) - A curated list of HEP/EEP-enabled projects. `MIT`
- [Kamailio](https://github.com/kamailio/kamailio) - SIP proxy server. `C`
- [OpenSIPS](https://github.com/OpenSIPS/opensips) - SIP proxy server.
- [FusionPBX](https://github.com/fusionpbx/fusionpbx) - Multi-tenant web interface that many people run on top of FreeSWITCH. `PHP`
- [jambonz-feature-server](https://github.com/jambonz/jambonz-feature-server) - Open-source CPaaS: drachtio for SIP, FreeSWITCH for media, webhook and WebSocket APIs. `MIT` `JavaScript`
- [drachtio-server](https://github.com/drachtio/drachtio-server) - SIP server controlled from Node.js, the signaling half of jambonz. `C++`
- [BigBlueButton](https://github.com/bigbluebutton/bigbluebutton) - Web conferencing for teaching. Its audio mixing runs on FreeSWITCH. `LGPL-3.0`
- [rtpengine](https://github.com/sipwise/rtpengine) - RTP proxy and media relay for NAT traversal, recording and transcoding. `GPL-3.0`
- [coturn](https://github.com/coturn/coturn) - The STUN and TURN server most WebRTC deployments end up running. `C`
- [FreeSBC](https://github.com/rasonyang/freesbc) - An SBC in Go that sits in front of FreeSWITCH: SIP over UDP/WS/WSS, in-process RTP relay, SDES-SRTP and WebRTC (ICE-Lite, DTLS-SRTP), configured from one YAML file. `Apache-2.0` `Go`
- [RustPBX](https://github.com/restsend/rustpbx) - Software-defined PBX in Rust: full SIP stack (UDP/TCP/WS/TLS/WebRTC), RTP relay and transcoding, webhook routing plus WebSocket real-time call control (RWI), AI voice agents as call participants, built-in web console. No C modules, no recompilation. `MIT` `Rust`
- [RSIPStack](https://github.com/restsend/rsipstack) - RFC 3261/3262-compliant SIP stack in Rust: UDP/TCP/TLS/WebSocket transports, transaction and dialog layers, digest auth, PRACK. Build SIP proxies, registrars, user agents or WebRTC SBCs; it also runs no_std on embassy-based embedded targets. `MIT` `Rust`
- [RustRTC](https://github.com/restsend/rustrtc) - High-performance real-time communication library in Rust: WebRTC, RTP/SRTP and T.38 fax behind a unified PeerConnection API, full ICE/STUN/TURN support, plus UPnP NAT traversal. Benchmarked at ~3.3x the throughput of webrtc-rs. `MIT` `Rust`
- [CGRates](https://github.com/cgrates/cgrates) - Real-time charging and billing system for telecom. `AGPL-3.0` `Go`
- [Janus](https://janus.conf.meetecho.com/) - WebRTC gateway and media server.
- [mediasoup](https://mediasoup.org/) - WebRTC SFU media server.

## Others

- [awesome-webrtc](https://github.com/cameronroe/awesome-webrtc) - A curated list of awesome WebRTC modules and resources. `CC0-1.0`
- [awesome-rtc](https://github.com/rtckit/awesome-rtc) - A curated list of real-time communication resources. `CC0-1.0`
- [awesome](https://github.com/sindresorhus/awesome) - A curated list of awesome lists on all kinds of topics. `CC0-1.0`
- [react-native-webrtc](https://github.com/react-native-webrtc/react-native-webrtc) - WebRTC support for React Native apps. `MIT`
- [webrtc-build](https://github.com/shiguredo-webrtc-build/webrtc-build) - WebRTC build scripts and prebuilt binaries.

FreeSWITCH-CN WeChat Official Account

![FreeSWITCH-CN WeChat Official Account](img/qrcode_for_FreeSWITCH-CN-wechat.jpg)

## Out-dated

Kept for reference. These links are dead, archived or no longer maintained.

- [GitMemory](https://www.gitmemory.com/signalwire/freeswitch) - GitMemory snapshot of FreeSWITCH. The service has shut down.
- [WebRTC.work](https://webrtcwork.com/) - A space dedicated to making WebRTC work easier. The domain no longer resolves.
- [SimpleDemo-jQueryVertoJS](https://github.com/Mazuh/SimpleDemo-jQueryVertoJS) - Simple jQuery Verto video conference demo. Archived by its author.

## Contributing

Contributions are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md) for what we accept, the entry format and the tag rules. Thanks to all [contributors](https://github.com/rts-cn/awesome-freeswitch/graphs/contributors); you rock!

## License

[CC0 1.0 Universal](LICENSE)

## Star History

[![Star History Chart](https://api.star-history.com/chart?repos=rts-cn/awesome-freeswitch&type=date&legend=top-left)](https://www.star-history.com/?repos=rts-cn%2Fawesome-freeswitch&type=date&legend=top-left)
