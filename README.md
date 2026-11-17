# Hi, I'm Kunkka 👋

**Hardware × AI × CAD**  
Building practical tools from everyday product work.  
从产品工作里的具体问题出发，把想法做成可用工具。

[English](#english) · [中文](#中文介绍) · [Selected projects / 代表项目](#selected-projects) · [More projects / 更多项目](#more-projects) · [X / Twitter](https://x.com/Svenu1s5)

## English

I build and explore tools for hardware product work: AI workflows, CAD and structural review, audio comparison, and local automation. My projects connect product information, engineering evidence, and hands-on tools that people can inspect and improve.

I care about editable source, traceable results, and clear validation boundaries. Alongside engineering tools, I also make small browser utilities and experiment with games.

## 中文介绍

我围绕硬件产品工作开发和探索工具，涉及 AI 工作流、CAD 与结构评审、收音对比和本地自动化，希望把产品资料、工程依据与实际操作连接起来。

我重视可编辑的源码、可追溯的结果，以及清楚的验证边界。除了工程工具，也做一些日常浏览器小工具，偶尔尝试游戏开发。

<a id="selected-projects"></a>
## Selected projects / 代表项目

| Project / 项目 | What it does & current scope / 用途与当前范围 |
| --- | --- |
| **[VoiceBench](https://github.com/SvenKunkka/voicebench)**<br>Audio comparison · 收音对比 | Record, replay, and compare voice recordings, with quality metrics, transcript checks, and exportable reports. Browser and local editions are available; their Whisper models differ, so recognition scores should not be mixed.<br>录音、回听与收音分析，提供质量指标、原稿核对和报告导出。有在线版与本机版；两版识别模型不同，识别评分不可混排。 |
| **[AI Product Knowledge Chain](https://github.com/SvenKunkka/ai-product-knowledge-chain)**<br>AI 产品知识链 | Links product versions, source documents, test evidence, and review records across new products, firmware changes, and support feedback. A single-user local prototype with simulated review roles and publishing channels.<br>串联产品版本、资料原文、测试依据和审核记录，覆盖新品、固件变更与售后反馈。当前为单用户本机原型，审核角色与发布渠道均为模拟。 |
| **[STEP Sixview](https://github.com/SvenKunkka/step-sixview)**<br>CAD drawings · 六视图 | Generates six orthographic visible-line views from STEP/STP, with editable SVG, PNG, and a PDF at 1:1 physical scale. Tested on Apple Silicon macOS; outputs are appearance line drawings, without manufacturing dimensions or tolerances.<br>将 STEP/STP 投影为六视图，输出可编辑 SVG、PNG 与 1:1 PDF。已在 Apple Silicon macOS 测试；输出为外观线稿，不包含制造尺寸与公差。 |
| **[3D Structure Review](https://github.com/SvenKunkka/3d-structure-review)**<br>Codex Skill · 结构评审 | Connects requirements and local CAD checks to structural, pre-tooling, and injection-molding risk reports. A reusable review workflow; geometry checks do not replace mold-flow analysis, physical tests, or production approval.<br>结合配置要求与本机 CAD，形成结构、开模前及注塑风险报告。属于可复用评审流程；几何检查不能代替模流、实物测试或量产签核。 |
| **[Keychron Smart Home Bridge](https://github.com/SvenKunkka/keychron-smart-home-bridge)**<br>Hardware interaction · 键盘与家居 | Connects keyboard Raw HID reports to Home Assistant through a Python bridge, with service triggers and LED feedback. QMK compilation and host simulation are recorded; ZMK compilation and real-device / live Home Assistant tests remain unverified.<br>通过 Python 桥接键盘 Raw HID 与 Home Assistant，实现服务触发和灯光反馈。已有 QMK 编译与主机模拟记录；ZMK 编译、真实键盘及实际 Home Assistant 联调尚未验证。 |
| **[Emberfall: Lone Survivor](https://github.com/SvenKunkka/emberfall-chromatic)**<br>Game Boy Color · 余烬独行 | A native Game Boy Color arena survival game built for ModRetro Chromatic, with ten combat stages and a browser demo. Emulator playthroughs are documented; physical Chromatic play has not been tested.<br>面向 ModRetro Chromatic 的原生 GBC 生存闯关游戏，包含十个战斗阶段和浏览器试玩。已记录模拟器通关验证，尚未在物理 Chromatic 上测试。 |

### Try something / 直接体验

- **[VoiceBench online / 在线收音对比](https://voicebench-online.yujianxi0.chatgpt.site)** — No installation; recordings and results stay in your browser. 无需安装，录音与结果保存在访问者自己的浏览器。
- **[Play Emberfall / 试玩余烬独行](https://svenkunkka.github.io/emberfall-chromatic/)** — Browser demo of the GBC game. 在浏览器里体验 GBC 游戏。
- **[Vibe Recorder](https://github.com/SvenKunkka/vibe-recorder)** — A lightweight WAV recorder with a browser-local library. [Download the single-file edition](https://github.com/SvenKunkka/vibe-recorder/releases/latest/download/Vibe-Recorder.html); see the repository for browser and launch-mode compatibility.<br>轻量 WAV 录音工具，支持浏览器本地录音库。可下载单文件版；浏览器与打开方式的兼容范围见仓库说明。

<a id="more-projects"></a>
## More projects / 更多项目

Explore by topic; each repository documents its own setup and validation scope.  
按方向浏览，安装方式与验证范围以各仓库说明为准。

| Area / 方向 | Repositories / 项目入口 |
| --- | --- |
| **AI & knowledge workflows / AI 与知识工作流** | [Ensemble / 合奏](https://github.com/SvenKunkka/ensemble-personal-assistant) · [AI Dev Team](https://github.com/SvenKunkka/auto-dev-team) · [Feishu × Codex × Obsidian Bridge](https://github.com/SvenKunkka/feishu-codex-obsidian-bridge) |
| **CAD & visualization / CAD 与可视化** | [OpenCAD-UX](https://github.com/SvenKunkka/OpenCAD-UX) · [STEP CMF Render Studio](https://github.com/SvenKunkka/step-cmf-render-studio) · [Blender Harness](https://github.com/SvenKunkka/blender-harness) |
| **Hardware & firmware / 硬件与固件** | [OpenHardwareOS](https://github.com/SvenKunkka/OpenHardwareOS) · [QMK Vibe Bridge](https://github.com/SvenKunkka/qmk-vibe-bridge) · [Firmware Reverse Engineering Skill](https://github.com/SvenKunkka/firmware-reverse-engineering-skill) |
| **Everyday tools / 日常工具** | [Vibe Recorder](https://github.com/SvenKunkka/vibe-recorder) · [Product Page Audit](https://github.com/SvenKunkka/product-page-audit) · [Review Radar](https://github.com/SvenKunkka/review-radar) |

## How I work / 我的做法

- Start with a concrete problem and a useful, inspectable result. 从具体问题出发，交付可以使用和检查的结果。
- Keep source files editable and conclusions tied to evidence. 保留可编辑源文件，让结论能追溯到依据。
- Document what was tested and what still needs real-world validation. 记录已测范围，以及仍需实际环境验证的部分。

These are personal projects and experiments. Licenses, upstream credits, compatibility, and validation records live in the individual repositories. Forks and learning resources retain their original authorship.

这里包含个人项目、实验、学习资料与上游 Fork。许可证、原作者归属、兼容性及验证记录见对应仓库；项目介绍不代表相关厂商背书。

## Connect / 联系我

Find me on **[X / Twitter · @Svenu1s5](https://x.com/Svenu1s5)** to talk about hardware, AI, CAD, and useful little tools. For project questions and suggestions, please open an Issue in the relevant repository.

在 **[X / Twitter · @Svenu1s5](https://x.com/Svenu1s5)** 交流硬件、AI、CAD 和实用小工具。具体项目的问题与建议，欢迎提交到对应仓库的 Issues。

[Browse all repositories / 浏览全部项目 →](https://github.com/SvenKunkka?tab=repositories)

<sub>Project summaries reviewed on 2026-11-17 · 项目介绍核对日期：2026-11-17</sub>
