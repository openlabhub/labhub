<p align="center">
  <img src="https://raw.githubusercontent.com/openlabhub/labhub/main/images/wechat-qrcode.jpg" width="120" alt="LabHub">
</p>

<h1 align="center">LabHub</h1>

<p align="center">
  <strong>把开源项目跑进真实硬件，用数据说话。</strong>
</p>

<p align="center">
  <a href="https://github.com/openlabhub/labhub/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License"></a>
  <a href="#contributing"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
  <img src="https://img.shields.io/badge/platform-Embedded%20%7C%20Linux%20%7C%20AI-orange.svg" alt="Platform">
</p>

---

## 关于 LabHub

LabHub 是一个**嵌入式开源项目实测实验室**。我们聚焦 GitHub 和芯片厂商的开源项目，把它们跑在真实硬件上，用实验数据说话。

我们覆盖的方向：

| 方向 | 做什么 |
|:--:|------|
| 📦 **开源项目实战** | ESP32 / STM32 / RP2040 / FPGA 真实跑通教程 |
| ⚙️ **源码拆解** | 操作系统内核、文件系统、通信协议栈深度解读 |
| 🖥️ **板卡实测** | 端侧 AI 推理、边缘计算开发板上手 |
| 🤖 **端侧 AI** | LLM 量化部署、TinyML、NPU 推理实测 |
| 🐧 **Linux 内核** | eBPF、内核模块、调度器、驱动编程 |

每一篇文章都是**可复现的实验报告**——你拿到同样的硬件，照着做就能跑通。

---

## 精选文章

> **阅读方式**：关注公众号 LabHub → 点击右上角 🔍 → 搜索文章标题即可阅读全文。
> 更多文章见 [完整目录 →](./articles/README.md)

### ESP32 / 单片机实战

| 文章 | 简介 |
|------|------|
| ESP32 驱动 WS2812B：用 RMT 外设 + DMA 实现零 CPU 占用 | 2 行 DMA 描述符，CPU 完全解放 |
| ESP32 Bit Pirate：把 ESP32-S3 变成全协议硬件调试工作台 | 一款 5 欧元的多合一硬件调试工具 |
| GitHub 开源 ESPHome：用 YAML 给 ESP32 写固件 | 零代码接入 Home Assistant 智能家居 |
| GitHub 开源 WLED：一个 ESP32 固件塞进 15 种灯光协议 | 刷一次固件变灯光控制器 |

### Linux 内核 / 驱动

| 文章 | 简介 |
|------|------|
| 手写你的第一个字符设备驱动 | 从一个不能卸载的内核模块说起 |
| sched_ext：20 行 BPF 接管进程调度 | Linux 内核调度器可编程时代来了 |
| 不用写一行 C：用 Rust 写你的第一个 eBPF 内核程序 | Rust + Aya 框架开发 eBPF 程序 |
| Platform Driver + Device Tree | 让内核自动发现你的硬件 |

### FPGA / 开源硬件

| 文章 | 简介 |
|------|------|
| GitHub 开源 LiteX：用 Python 写 FPGA，一行命令搭 RISC-V SoC | 告别 Vivado，全开源工具链 |
| GitHub 开源 Icestorm：反向破译 FPGA，全开源工具链 | FOSS FPGA 工具链完整教程 |
| GitHub 开源 Cynthion：一块 FPGA 板分析所有 USB 2.0 通信 | $149 的 USB 分析仪 |
| GitHub 开源矿渣利用：￥30 买 Zynq 开发板跑 Linux | 矿机拆芯片手焊开发板 |

### 端侧 AI / 推理

| 文章 | 简介 |
|------|------|
| 一块树莓派、30 分钟：在本地跑通你的第一个 LLM | llama.cpp 端侧部署入门 |
| GitHub 开源 bbTalkie：ESP32-S3 做的 AI 对讲机 | 免按键，语音直接对话 |
| 23 倍吞吐量的秘密：拆解 PagedAttention 的内存虚拟化设计 | vLLM 核心技术深度解读 |
| llama.cpp 量化格式完全搞懂：Q4_K_M、GGUF、IQ3 | 模型量化选型指南 |

### 源码拆解

| 文章 | 简介 |
|------|------|
| minicoro：协程切换不过是存 7 个寄存器 | 4 个 API 实现跨平台无栈协程 |
| genann：400 行 C 代码跑通反向传播 | 从零手写神经网络 |
| ds4：Redis 作者 antirez 用纯 C 实现 DeepSeek 本地推理 | 工业级推理引擎架构拆解 |
| RCU 基础：读端零锁的代价是什么 | Linux 内核最精妙的并发机制 |

---

## 关注我们

### 微信公众号

公众号是 LabHub 的内容主阵地。扫码关注，不错过每一篇实测教程。

<p align="center">
  <img src="https://raw.githubusercontent.com/openlabhub/labhub/main/images/wechat-qrcode.jpg" width="200" alt="LabHub 公众号">
</p>

<p align="center">
  <b>微信号：OpenLabHub</b> &nbsp;|&nbsp; 公众号：LabHub
</p>

### 技术交流群

添加微信 `OpenLabHub` 备注「GitHub」，拉你进嵌入式开源技术交流群。

群里讨论：
- 开源项目上手问题
- 嵌入式硬件选型
- 端侧 AI 部署踩坑
- Linux 内核/驱动技术交流

---

## 投稿 & 项目推广

如果你有自己的开源项目（或者发现了好项目），欢迎投稿。我们会在公众号上撰写实测文章推广。

### 投稿要求

- 项目必须是**真实可运行的开源软硬件项目**
- 提供项目 GitHub 链接、硬件清单、功能说明
- 可选提供你的个人/团队介绍，文章署名你

### 投稿方式

1. **发邮件**：labhub@yeah.net，标题注明「项目投稿」
2. **提 Issue**：在本仓库 [Issues](https://github.com/openlabhub/labhub/issues) 区提交，选择「项目投稿」模板
3. **微信群**：加入技术交流群直接联系

---

## 赞助 & 捐赠

如果你觉得 LabHub 的内容对你有帮助，欢迎赞助支持，让我们持续产出高质量的技术教程。

<p align="center">
  <img src="https://raw.githubusercontent.com/openlabhub/labhub/main/donate/wechat-reward.png" width="200" alt="微信赞赏">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/openlabhub/labhub/main/donate/alipay.jpg" width="200" alt="支付宝赞赏">
</p>

<p align="center">
  微信赞赏 &nbsp;&nbsp;|&nbsp;&nbsp; 支付宝赞赏
</p>

---

## 星标历史

如果这个仓库对你有帮助，点个 Star 支持一下。

<a href="https://star-history.com/#openlabhub/labhub&Date">
  <img src="https://api.star-history.com/svg?repos=openlabhub/labhub&type=Date" alt="Star History Chart">
</a>

---

## 关于作者

十年嵌入式老兵，从裸机到 Linux，从单片机到端侧 AI。相信「代码 + 数据 > 观点」，坚持每篇文章都可复现。

- 📧 联系邮箱：labhub@yeah.net
- 🔗 合作 / 项目推广 / 广告投放 欢迎联系

---

<p align="center">
  <sub>Made with ❤️ by <a href="https://github.com/openlabhub">openlabhub</a></sub>
</p>
