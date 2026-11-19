# Awesome-AI-Computer-Use-OS-Automation

# Top AI Computer Use & OS Automation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on GUI Vision-Action Agents, Desktop OS Automation, Sandboxed Virtual Desktops, Browser-Use & Cross-Platform RPA*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Computer Use & OS Automation**. These tools enable multimodal AI agents to perceive desktop screens, control mouse cursors and keyboards, operate native Windows/macOS/Linux GUI applications, automate web browsers, and run inside isolated virtual desktop sandboxes.

**Examples** include Anthropic Computer Use, OpenAI Operator / CUA, Adept, MultiOn, Simular, HyperWrite, Induced AI, Lindy, Browserbase, Playwright Cloud, and alexshpunt/pi-agent-computer-use (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for local desktop GUI agents (`UI-TARS`, `OSWorld`, `Open Interpreter`, `Self-Operating Computer`, `Agent S`), containerized desktop sandboxes (`CUA / TryCua`, `ByteBot`), screen-parsing models (`OmniParser`), and cross-platform automation SDKs — ideal for AI agent researchers, RPA engineers, and builders automating native operating systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Anthropic Computer Use (Claude API)](https://anthropic.com)**  
  Cloud multimodal vision-and-action capability allowing Claude models to inspect desktop screenshots, calculate pixel coordinates, and execute mouse clicks, keystrokes, and bash commands.

- **[OpenAI Operator & Computer-Using Agent (CUA)](https://openai.com)**  
  Cloud AI agent system combining GPT-4o/o-series vision reasoning with reinforcement-learned GUI interaction to autonomously navigate browsers and web applications.

- **[Simular](https://simular.ai)**  
  Cloud and desktop AI computer-use agent platform built on Agent S architecture capable of executing complex, multi-application workflows across macOS and Windows.

- **[MultiOn](https://multion.ai)**  
  Cloud personal and enterprise web-agent platform enabling AI agents to autonomously operate web browsers, fill forms, and complete multi-step online tasks via API.

- **[Browserbase](https://browserbase.com)**  
  Serverless headless browser infrastructure built for AI agents and Playwright/Stagehand automation featuring session replays, stealth mode, and persistent contexts.

- **[Lindy](https://lindy.ai)**  
  No-code cloud AI assistant and workflow automation platform enabling teams to deploy computer-using and API-connected agents across email, CRM, and browser tasks.

- **[HyperWrite (Personal Assistant)](https://hyperwriteai.com)**  
  Cloud AI browser companion and autonomous web-navigation agent capable of executing multi-step research, form filling, and web workflows on behalf of users.

- **[Induced AI](https://induced.ai)**  
  Cloud browser-automation and RPA platform translating natural-language workflows into parallelized headless browser executions without brittle selectors.

- **[Adept](https://adept.ai)**  
  Enterprise AI action-model pioneer focused on multimodal software-control agents that operate complex enterprise web and desktop interfaces.

- **[Scrapybara / Orgo Cloud](https://orgo.ai)**  
  Cloud virtual desktop infrastructure providing instant, API-controllable Linux/Windows VM sandboxes tailored specifically for Computer-Use AI agents.


## Open-Source GitHub Projects

- **[alexshpunt/pi-agent-computer-use](https://github.com)**  
  Open-source computer-use extension and agent toolkit built for the Pi coding/desktop agent ecosystem enabling screen observation, mouse/keyboard GUI control, and OS-level task execution.

- **[CUA (`trycua/cua`)](https://github.com)**  
  Comprehensive open-source (`MIT`) Computer-Use Agent framework and high-speed macOS/Linux virtualization sandbox (`Lume`) enabling local and cloud vision models to safely control full operating systems.

- **[ByteBot (`bytebot-ai/bytebot`)](https://github.com)**  
  Self-hosted open-source (`Apache-2.0`) AI desktop agent packaged with a full containerized Linux desktop environment, task queue, human takeover UI, and Anthropic/OpenAI/local model support.

- **[UI-TARS (`bytedance/UI-TARS` & `UI-TARS-desktop`)](https://github.com)**  
  Leading open-source (`Apache-2.0`) native GUI agent model and cross-platform desktop application from ByteDance capable of perceiving screens and operating Windows, macOS, and mobile apps natively.

- **[Agent S (`simular-ai/Agent-S`)](https://github.com)**  
  Open-source (`Apache-2.0`) agentic framework for autonomous computer interaction combining experience-augmented hierarchical planning with grounding models across Ubuntu, Windows, and macOS.

- **[OSWorld (`xlang-ai/OSWorld`)](https://github.com)**  
  Foundational open-source (`Apache-2.0`) executable desktop environment and benchmark suite evaluating multimodal computer-use agents across real Ubuntu, Windows, and macOS applications.

- **[Open Interpreter (`OpenInterpreter/open-interpreter`)](https://github.com)**  
  Popular open-source (`AGPL-3.0`) natural-language OS interface allowing LLMs to execute Python, Bash, AppleScript, and GUI automation commands locally on your computer.

- **[Self-Operating Computer (`OthersideAI/self-operating-computer`)](https://github.com)**  
  Open-source (`MIT`) framework enabling multimodal vision models to view the screen and operate keyboard and mouse inputs like a human operator across macOS, Windows, and Linux.

- **[OmniParser (`microsoft/OmniParser`)](https://github.com)**  
  Open-source (`MIT`) screen-parsing vision toolkit from Microsoft that converts raw UI screenshots into structured, clickable element bounding boxes and semantic descriptions for vision-based GUI agents.

- **[ShowUI (`showlab/ShowUI`)](https://github.com)**  
  Open-source (`Apache-2.0`) lightweight 2B-parameter Vision-Language-Action (VLA) model engineered specifically for fast UI visual grounding and GUI navigation.

- **[ScreenSpot / OS-Atlas (`OS-Copilot/OS-Atlas`)](https://github.com)**  
  Open-source foundation GUI action model and multi-platform grounding dataset enabling vision agents to accurately localize buttons, icons, and text fields across desktop, web, and mobile OSs.

- **[Browser-Use (`browser-use/browser-use`)](https://github.com)**  
  Leading open-source (`MIT`) web-agent framework connecting LLMs directly to Playwright browsers via indexed DOM and vision extraction for autonomous web workflows.

- **[Skyvern (`Skyvern-AI/skyvern`)](https://github.com)**  
  Open-source (`AGPL-3.0`) vision-LLM browser automation platform automating complex web portal workflows without brittle XPath or CSS selectors.

- **[UFO (`microsoft/UFO`)](https://github.com)**  
  Open-source (`MIT`) UI-Focused Agent from Microsoft designed specifically for automating multi-application workflows natively on Windows OS via Windows UI Automation APIs and vision.

- **[PyAutoGUI (`asweigart/pyautogui`) & Nut.js (`nut-tree/nut.js`)](https://github.com)**  
  Battle-tested open-source (`BSD-3-Clause` / `MIT`) cross-platform GUI automation libraries providing programmatic mouse control, keyboard typing, and screenshot capture for Python and Node.js.

- **[Anthropic Computer Use Reference Demo (`anthropics/anthropic-quickstarts`)](https://github.com)**  
  Official open-source (`MIT`) Dockerized Ubuntu X11 virtual desktop reference implementation demonstrating Claude Computer Use with VNC streaming and `xdotool` execution.

### Additional Strong Open-Source Options

- **[Midscene.js (`web-infra-dev/midscene`)](https://github.com)** and **[Mobile-Agent (`X-PLUG/MobileAgent`)](https://github.com)** for visual-driven AI GUI automation across Android, iOS, and mobile simulators via ADB.
- **[Terminator (`mediar-ai/terminator`)](https://github.com)** and **[Screenpipe (`mediar-ai/screenpipe`)](https://github.com)** for OS accessibility-tree automation and 24/7 local screen/audio context recording feeding desktop AI agents.
- **[Playwright (`microsoft/playwright`)](https://github.com)** and **[Playwright MCP (`microsoft/playwright-mcp`)](https://github.com-mcp)** for deterministic browser control and accessibility-snapshot MCP integration.
- **[Kasm Workspaces / Neko (`m1k1o/neko`)](https://github.com)** for lightweight Dockerized WebRTC virtual desktops ideal for isolating autonomous computer-use agents.
- **[sikulix (`RaiMan/SikuliX1`)](https://github.com)** and **[TagUI (`aisingapore/TagUI`)](https://github.com)** for open-source visual template-matching and natural-language Robotic Process Automation (RPA).

**Frameworks for building custom systems**: Combine **alexshpunt/pi-agent-computer-use** or **CUA (`trycua/cua`)** with **UI-TARS / OmniParser** (GUI vision & grounding), **ByteBot / Docker X11** (sandboxed OS isolation), and **Browser-Use** (web tasks) for safe, end-to-end open-source computer-use automation.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
