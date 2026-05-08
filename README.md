<h1 align="center">MarsDoge</h1>

<p align="center">
  <strong>Firmware · LoongArch · UEFI/EDK II · ROCm · AI-assisted Engineering</strong>
</p>

<p align="center">
  Dongyan Qian · Beijing, China · UEFI Development @ Loongson Technology Co., Ltd.
</p>

<p align="center">
  <a href="https://mars.dogexorg.com/blog">Blog</a> ·
  <a href="https://github.com/MarsDoge">GitHub</a> ·
  <a href="https://x.com/MarsDogeCo">X / Twitter</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Firmware-UEFI%20%2F%20EDK%20II-111827?style=flat-square" alt="Firmware: UEFI / EDK II" />
  <img src="https://img.shields.io/badge/Architecture-LoongArch-7f1d1d?style=flat-square" alt="Architecture: LoongArch" />
  <img src="https://img.shields.io/badge/Systems-Linux%20%2F%20Platform-0f172a?style=flat-square" alt="Systems: Linux / Platform" />
  <img src="https://img.shields.io/badge/Workflow-AI--assisted-2563eb?style=flat-square" alt="Workflow: AI-assisted" />
</p>

---

## About

I work close to hardware: firmware, boot flows, platform enablement, runtime compatibility, and the tooling that makes low-level engineering easier to inspect and reproduce.

喜欢把底层系统问题拆开、验证、修好，然后写下来。

My day-to-day work sits between firmware implementation, debugging traces, build systems, and practical automation. I care about small, explainable changes and documentation that survives beyond a single debugging session.

---

## Focus

- UEFI firmware development and EDK II workflows
- LoongArch platform enablement and low-level system software
- Firmware debugging, boot flow analysis, and platform bring-up
- C / C++ / Shell / Python tooling for systems engineering
- ROCm, GPU runtime, and cross-architecture compatibility experiments
- AI-assisted review, translation, documentation, and automation loops
- Turning debugging notes into reusable technical writing

---

## Selected projects

| Project | Area | Notes |
|---|---|---|
| [OsTools](https://github.com/MarsDoge/OsTools) | LoongArch / Systems | Platform utility toolkit for register reading, firmware updates, and hardware status checks |
| [llm-translate](https://github.com/MarsDoge/llm-translate) | AI tooling | Multi-provider translation workflow for CLI and editor use |
| [persona-distillation-lab](https://github.com/MarsDoge/persona-distillation-lab) | AI agents | Experiments around reusable agent skills, behavior, and cognitive distillation |
| [openclaw-community](https://github.com/MarsDoge/openclaw-community) | Agents / Community | Community work around OpenClaw-style agent workflows |
| [ollama-gpt](https://github.com/MarsDoge/ollama-gpt) | Local LLM | Experiments with local and self-hosted model workflows |

Some repositories are experiments, notes, or work-in-progress labs. I prefer small, inspectable tools over large opaque abstractions.

---

## Stack

### Firmware / platform

![UEFI](https://img.shields.io/badge/UEFI-Firmware-111827?style=flat-square)
![EDK II](https://img.shields.io/badge/EDK%20II-Platform%20Firmware-1f2937?style=flat-square)
![LoongArch](https://img.shields.io/badge/LoongArch-Architecture-7f1d1d?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-Systems-0f172a?style=flat-square)
![ROCm](https://img.shields.io/badge/ROCm-Runtime-ef4444?style=flat-square)

### Languages and tooling

![C](https://img.shields.io/badge/C-Low%20Level-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-Systems-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-Automation-121011?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-Tooling-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-Review%20%2F%20Bisect-F05032?style=flat-square&logo=git&logoColor=white)

### Daily engineering

- Firmware logs, serial consoles, QEMU, and platform traces
- Patch review, bisect-driven debugging, and reproducible test notes
- Build systems, scripts, and local-first development environments
- LLM-assisted workflows where they improve feedback loops and reduce repetitive work

---

## Engineering notes

> Understand the boot path before changing the boot path.

- Make debugging artifacts useful: logs, notes, reproduction steps, and minimal patches.
- Prefer boring, reliable tools for critical paths.
- Keep abstractions honest; low-level systems do not forgive vague assumptions.
- Optimize for reproducibility before cleverness.
- Automate repeated work, but keep the escape hatch visible.
- Use AI as a review and exploration assistant, not as a replacement for engineering judgment.

少一点玄学，多一点证据。

---

## AI-assisted workflow

I use AI tools as part of a practical engineering loop: collect context, inspect code and logs, generate hypotheses, make small changes, review diffs, test results, and document what was learned.

The goal is not to chase every new model. The goal is to reduce friction in reading, debugging, translating, testing, and documenting complex systems.

---

## Writing and contact

I write about firmware, system software, LoongArch, AI tooling, and engineering notes.

- Blog: https://mars.dogexorg.com/blog
- GitHub: https://github.com/MarsDoge
- X / Twitter: https://x.com/MarsDogeCo
- Location: Beijing, China

For technical discussion, GitHub issues and discussions are usually the best starting point.

---

## GitHub stats

<p align="center">
  <picture>
    <source
      srcset="https://github-readme-stats.vercel.app/api?username=MarsDoge&show_icons=true&theme=github_dark&hide_border=true"
      media="(prefers-color-scheme: dark)"
    />
    <source
      srcset="https://github-readme-stats.vercel.app/api?username=MarsDoge&show_icons=true&theme=default&hide_border=true"
      media="(prefers-color-scheme: light)"
    />
    <img
      src="https://github-readme-stats.vercel.app/api?username=MarsDoge&show_icons=true&theme=github_dark&hide_border=true"
      alt="MarsDoge GitHub stats"
    />
  </picture>
</p>

<p align="center">
  <picture>
    <source
      srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=MarsDoge&layout=compact&theme=github_dark&hide_border=true"
      media="(prefers-color-scheme: dark)"
    />
    <source
      srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=MarsDoge&layout=compact&theme=default&hide_border=true"
      media="(prefers-color-scheme: light)"
    />
    <img
      src="https://github-readme-stats.vercel.app/api/top-langs/?username=MarsDoge&layout=compact&theme=github_dark&hide_border=true"
      alt="MarsDoge top languages"
    />
  </picture>
</p>
