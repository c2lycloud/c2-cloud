# C2 Cloud

Your Claude Code, running in your own cloud workspace: give it a task, close your laptop, and it keeps working.
This repository holds the **installers only**. Website, plans and help: **https://c2ly.cloud**

**[Download the latest version](../../releases/latest)**

| System | File |
| --- | --- |
| macOS, Apple silicon (M1 and later) | `C2-Cloud-mac.zip` |
| Windows 10 and 11, 64-bit | `C2-Cloud-setup.exe` |
| Debian / Ubuntu | `C2-Cloud-amd64.deb` |
| Other Linux, x86_64 | `C2-Cloud-x86_64.AppImage` |

Once installed, the app updates itself. Every update is checked against a signature built into the app before it is installed (`manifest.json` and `manifest.json.sig` in each release list each file's SHA-256).

## Before you start

- You need a C2 Cloud plan (from https://c2ly.cloud) and **your own Claude Pro or Max subscription**. Claude's free plan cannot run Claude Code.
- macOS: on first open, if macOS says it cannot verify the developer, go to System Settings → Privacy & Security and click "Open Anyway".
- Windows: if SmartScreen says it protected your PC, click "More info", then "Run anyway".
- Linux AppImage: `chmod +x` it first; it needs FUSE 2 (`libfuse2t64` on Ubuntu 24.04 and later).

Then open C2 Cloud and enter the activation key from your email.

## 中文

C2 Cloud：你的 Claude Code 在云端独享的工作间里运行，合上电脑也继续工作。这里只放安装包；官网、套餐和帮助请看 **https://c2ly.cloud**。

**[下载最新版本](../../releases/latest)**：macOS 选 `C2-Cloud-mac.zip`，Windows 选 `C2-Cloud-setup.exe`，Debian / Ubuntu 选 `.deb`，其他 Linux 选 `.AppImage`。装好后会自动更新，每次更新都先校验签名。

使用前需要：C2 Cloud 套餐，以及**你自己的 Claude Pro 或 Max 订阅**（Claude 免费版不能使用 Claude Code）。安装后打开 C2 Cloud，输入邮件里的激活码。

## Français

C2 Cloud : votre Claude Code dans votre propre espace de travail cloud ; il continue même ordinateur fermé. Ce dépôt ne contient que les installateurs ; site, formules et aide : **https://c2ly.cloud**.

**[Télécharger la dernière version](../../releases/latest)**. Il vous faut une formule C2 Cloud et **votre propre abonnement Claude Pro ou Max**. Ouvrez ensuite C2 Cloud et saisissez la clé d'activation reçue par e-mail.

---

Support: support@c2ly.cloud · Claude is a trademark of Anthropic, PBC. C2 Cloud is an independent hosting service, not affiliated with, endorsed or sponsored by Anthropic.
