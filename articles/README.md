# LabHub 文章目录

<p align="center">
  <img src="https://raw.githubusercontent.com/openlabhub/labhub/main/images/wechat-qrcode.jpg" width="180" alt="LabHub 公众号">
</p>

<p align="center">
  <b>扫码关注公众号 LabHub（微信号：OpenLabHub）</b>
</p>

---

## 如何阅读文章

1. **关注公众号** — 扫描上方二维码，或微信搜索 `OpenLabHub`
2. **号内搜索** — 进入公众号，点击右上角 🔍，输入文章标题关键词
3. **找到即读** — 号内搜会精确匹配标题，秒定位到目标文章

> 为什么不用直接链接？微信文章链接可能过期，且未认证账号 API 受限。
> 号内搜是**最可靠**的查找方式，一次关注，永久可查。

---

## ESP32 / 单片机实战

| 标题 |
|------|
| GitHub 开源 OpenDTU：￥50 替代天价光伏 DTU |
| GitHub 开源 FDRS：ESP-NOW 农场物联网方案 |
| GitHub 开源 ESP-AI：ESP32 零成本接入 AI 语音 |
| GitHub 开源 bbTalkie：ESP32 跑 AI 做免按键对讲机 |
| GitHub 开源 bbTalkie：ESP32-S3 做的 AI 对讲机 |
| GitHub 开源 WLED：ESP32 刷一次固件变灯光控制器 |
| 嵌入式 ESP32 驱动 WS2812B：用 RMT 外设 + DMA 实现零 CPU 占用 |
| GitHub 开源 ESPectre：€10 ESP32 Wi-Fi CSI 穿墙人体检测 |
| GitHub 开源 RKNN：3 行 Python，RK3588 NPU 跑 YOLOv8 |
| GitHub 开源 Tasmota：刷一次固件，告别厂商云 |
| GitHub 开源 ESPHome：用 YAML 给 ESP32 写固件 |
| ESP32 Bit Pirate：把 ESP32-S3 变成全协议硬件调试工作台 |
| esptool：ESP32 不只是烧录 |
| CANopenNode：在 STM32 上实现 CiA 301 标准 CANopen 从站 |
| TinyUSB：在 STM32 上实现自定义 USB HID 设备 |
| mquickjs：在 10KB 内存的单片机上跑 JavaScript |
| 用 Rust 写单片机：Embassy 替代 FreeRTOS，代码量减半还不怕内存 bug |
| EasyFlash：轻量级嵌入式 Flash 存储解决方案 |

---

## Linux 内核 / 驱动

| 标题 |
|------|
| Linux 内核 sched_ext：20 行 BPF 接管进程调度 |
| sched_ext：用 BPF 写一个自己的 CPU 调度器 |
| Linux 内核调度器正在被 Rust 重写：sched_ext 为什么重要 |
| 不用写一行 C：用 Rust 写你的第一个 eBPF 内核程序 |
| 从一个不能卸载的内核模块说起：手写你的第一个字符设备驱动 |
| 给 /dev/mylog 加上锁和 ioctl：一个能上生产的内核驱动长什么样 |
| 内核模块调试三板斧：printk 等级、ftrace 追踪、KGDB 远程调试 |
| 把 /dev/mylog 从 C 重写到 Rust：第一个 Rust 内核模块实战 |
| Platform Driver + Device Tree：让内核自动发现你的硬件 |
| GPIO + 中断：用按键唤醒你的驱动 |
| 不要直接操作 GPIO——用内核 LED 框架 |
| 用 kfifo 把 mylog 从玩具变成工具 |
| mmap 零拷贝：省掉每次 read 都要跑的 copy_to_user |
| 让 epoll 能监听你的设备：poll 实现实战 |
| 当内核有数据时主动通知你：SIGIO 异步信号 |
| 用 sysfs 给驱动开一扇参数配置窗口 |
| procfs：当你需要一个人类可读的状态面板 |
| Netlink：内核与用户态的高性能通信通道 |
| Kprobes：不重编译也能在任何内核函数上设断点 |
| 给你的驱动加上 tracepoint：让 ftrace 和 perf 都能追踪 |
| 故意让 kmalloc 失败：内核故障注入测试 |
| 内核定时器三件套：timer_list / hrtimer / workqueue 怎么选 |
| I2C 设备驱动实战：让内核认识你的 BME280 传感器 |
| DMA 基础：一次不经过 CPU 的内存搬运实验 |
| SPI 设备驱动实战：用 ADS1115 ADC 补齐总线的另一半 |
| Input 子系统：把 A2 的按键升级为标准输入设备 |
| KUnit：给你的驱动写第一个内核单元测试 |
| 电源管理：给你的 I2C 传感器加上 suspend/resume |
| 交叉编译指南：在 x86 上编译树莓派的内核模块 |
| compat_ioctl：当 32 位用户态调用 64 位内核的 ioctl |
| KASAN / KFENCE / KMEMLEAK：三大内存调试器实测 |
| DT Binding 文档：把你写的 labhub,mydevice 变成内核认可的标准绑定 |
| UIO 驱动：把 A2 的按键搬到用户态 |
| bpftrace 追踪内核模块：一行命令替代 kprobes 模块 |
| LabHub 内核模块实验路线图 — 树莓派版 |

---

## 内核算法专题

| 标题 |
|------|
| list_head：内核的侵入式链表 |
| rbtree：红黑树在 CFS 调度器里怎么用 |
| XArray：页缓存的核心索引——按整数键 O(1) 查找的树状数组 |
| RCU 基础：读端零锁的代价是什么 |
| 内核排序：sort() + list_sort() 实测对比 |
| 哈希表：内核的 hlist + 自定义哈希——按 PID 索引的内核对象缓存 |
| kfifo 内部实现拆解：手写一个无锁环形缓冲 |
| 位图操作：bitmap_* 和 cpumask——用 8 个字节管 64 个设备 ID |
| 引用计数：kref + kobject——多消费者共享内核对象的正确姿势 |
| 内存分配器内幕：slab 着色 + buddy 碎片——从 /proc/slabinfo 看真实消耗 |
| completion + 信号量：当 wait_queue 太重——等一次 vs 等很多次 |
| seqlock + rwlock：写者很少、读者极多时的终极优化 |
| Per-CPU 变量：为什么网络子系统和块层大量用 percpu 而不用锁 |

---

## FPGA / 开源硬件

| 标题 |
|------|
| GitHub 开源 Zynq 移植：矿机拆芯手焊 FPGA 开发板 |
| GitHub 开源矿渣利用：￥30 买 Zynq 开发板跑 Linux |
| GitHub 开源 lit3rick：pic0rick 作者的前一代 FPGA 超声板 |
| GitHub 开源 openwifi：WiFi MAC 层塞进 FPGA 实现 10μs SIFS |
| GitHub 开源 pic0rick：RP2040 做的超声测厚仪 |
| GitHub 开源 PIO-USB：RP2040 用 3 个状态机造出第二个 USB 口 |
| GitHub 开源 Cynthion：一块 FPGA 板分析所有 USB 2.0 通信 |
| GitHub 开源流片：花 $100，你的 Verilog 变成真的芯片 |
| GitHub 开源 Icestorm：反向破译 FPGA，全开源工具链 |
| GitHub 开源 LiteX：用 Python 写 FPGA，一行命令搭出 RISC-V SoC |
| GitHub 开源 OpenCat：12 舵机四足机器猫的开源步态 |
| NanoVNA：把万元仪器的 80% 功能塞进 200 块掌心 |
| Black Magic Probe：花 30 块做一个专业级 ARM 调试器 |
| 嵌入式调试器怎么选：J-Link vs CMSIS-DAP vs ST-Link |

---

## 端侧 AI / LLM

| 标题 |
|------|
| GitHub 开源 ESP-AI：ESP32 零成本接入 AI 语音 |
| GitHub 开源 bbTalkie：ESP32 跑 AI 做免按键对讲机 |
| GitHub 开源 ExecuTorch：Meta 的端侧推理引擎 |
| GitHub 开源 RKNN：3 行 Python，RK3588 NPU 跑 YOLOv8 |
| whisper.cpp：在树莓派上跑通端侧语音识别 |
| 2026 端侧 AI 开发板选购指南：50 元到 5000 元，实测数据帮你选 |
| Q4_K_M、GGUF、IQ3——llama.cpp 量化格式完全搞懂 |
| 29K Star、791 模型：llmfit 3 秒测出你的硬件能跑哪些本地大模型 |
| 一块树莓派、30 分钟：在本地跑通你的第一个 LLM |
| 200 行 Python 从零实现一个 RAG 系统 |
| 2000 元、一个周末：搭建你的第一个 AI 机械臂 |
| 23 倍吞吐量的秘密：拆解 PagedAttention 的内存虚拟化设计 |
| GitHub 开源 llamafile：一个文件在任何平台跑大模型 |
| ds4：Redis 作者 antirez 用纯 C 实现 DeepSeek 本地推理 |
| 当人形机器人年产量突破十万台，工程师的机会在哪里 |
| 腾讯混元Hy3实测：当大模型从"会聊天"变成"能干活" |
| 花 65 块钱，在一块比信用卡还小的 RISC-V 开发板上跑 AI |
| DeepSeek 为什么要自己造芯片？ |
| 英伟达 Jetson Orin Nano Super 实测 |
| 代码写得再烂能跑就行——架构烂了谁都跑不了：拆解 ArchGuard 的架构治理引擎 |

---

## 源码拆解

| 标题 |
|------|
| clay：4.8k 行 C 实现一个 Flexbox 布局引擎 |
| 只需 400 行 C 代码就能跑通神经网络：逐行拆解 genann |
| minicoro：协程切换不过是存 7 个寄存器 |
| ds4：Redis 作者 antirez 用纯 C 实现 DeepSeek 本地推理 |
| fasthttp：Go 的 HTTP 凭什么比 net/http 快 6 倍 |
| python3 -m http.server 源码拆解 |
| lwan / lighttpd：C 语言 HTTP 服务器的三代 I/O 演进 |
| darkhttpd 源码精读：一个 C 文件实现 HTTP 服务器 |
| 设备树编译器 dtc 源码解读 |
| cantools：Python 解析 CAN 总线 DBC 文件 |
| libgpiod：Linux 新一代 GPIO 接口 |
| picolibc：嵌入式 C 标准库 |
| probe-rs：扔掉 OpenOCD，一行命令烧写调试 Cortex-M |
| devmem2 源码精读：130 行 C 代码教你从用户空间直接操作硬件寄存器 |
| c-periphery 源码精读：一个 C 库统一 Linux 下 7 种外设访问 |
| pyelftools 源码精读：用 Python 解析你的固件 ELF 文件 |
| C/C++ 代码热重载神器 cr.h |
| GitHub 开源 log.c：给 C 项目加日志，两个文件 200 行 6 级日志 32 个回调 |

---

## 嵌入式 Linux / 系统

| 标题 |
|------|
| GitHub 开源 OpenWrt：4 步编译你自己的嵌入式路由器固件 |
| GitHub 开源 Pi-hole：树莓派全屋去广告，一行命令 |
| Linux 嵌入式 Buildroot：3 条命令从零构建完整 Linux 系统 |
| GitHub 开源 Pi-KVM：花 200 块把树莓派变成 IP-KVM |
| Caddy：自动 HTTPS 到底有多自动 |
| 轻量 HTTP 服务器横评：caddy vs fasthttp vs lwan vs lighttpd |
| tio：嵌入式开发者的现代串口终端 |
| I2C 死锁排查实录：从 SCL 被拉低到恢复通信 |
| 用 QEMU + Busybox + 自编译内核搭嵌入式 Linux 开发环境 |
| PX4 无人机开发的"万能遥控器"：MAVSDK 从入门到起飞 |
| Google 开源了一款不到 4KB 的嵌入式 Shell：esh |

---

## 开源项目评测 & 工具

| 标题 |
|------|
| GitHub 开源 RTL-SDR 超声：￥30 电视棒复现 B 超原理 |
| GitHub 开源 VisSonixAP：Zynq 超声成像方案 |
| GitHub 开源 OpenSimpleLidar：$35 自己做激光雷达 |
| 嵌入式 TLS 库怎么选？BearSSL 和 mbedTLS/wolfSSL 的实测对比 |
| 开源 RTOS Embox：在 STM32 上跑 Qt、OpenCV 和 PJSIP |
| 开源 IoT C 库 Gear-lib：POSIX C 搞定 RTSP/MQTT/音视频和事件驱动 |
| GitHub 开源 rtl_433：$10 电视棒解码所有 433MHz 设备 |
| 开源逻辑分析仪 PulseView：$10 硬件 + 免费软件 |
| GitHub 开源 GRBL：一块 Arduino 怎么变成 CNC 控制器 |
| GitHub 开源 MCUBoot：给 MCU 固件加上签名验证和安全 OTA |
| GitHub 开源 microps：逐行拆解嵌入式 TCP/IP 协议栈 |
| GitHub 开源 OpenThread：Google 的 Thread 协议栈 |
| GitHub 开源 PX4：12k Star 飞控的 uORB 消息总线 |
| GitHub 开源 Tock OS：5k Star 的 Rust RTOS |
| GitHub 开源 Zephyr：16k Star，Linux 基金会 RTOS |
| GitHub 开源 Marlin：2 个中断 + 1 循环，15 年多任务架构 |
| GitHub 开源 Klipper：11.7k Star，树莓派算轨迹 MCU 发脉冲 |
| GitHub 开源 ArduPilot：EKF 让无人机 GPS 断了也能飞 |
| GitHub 开源 Betaflight 飞控的双缓冲 DMA 技巧 |
| GitHub 开源 RT-Thread：一个对象容器管所有内核资源 |
| GitHub 开源 QMK：一个 uint32_t 管 32 层按键 |
| GitHub 开源 WLED：一个 ESP32 固件塞进 15 种灯光协议 |
| Mongoose：给嵌入式设备配一个全栈 Web 服务器，两个文件就够了 |
| MCUBoot：给 STM32 固件加上签名验证和安全 OTA |
| FatFs 曝 7 个 CVE：你的嵌入式设备可能在用有漏洞的文件系统 |
| GitHub 开源 AxxSolder：STM32 打造的 JBC 焊台控制器 |
| GitHub 开源 GNU Radio：拖拽方块就能做无线电信号处理 |
| GitHub 开源 LittleFS：ARM 为 MCU 设计的文件系统 |
| STM32 HardFault 调试实战：3 步从寄存器反推崩溃现场 |
| Zephyr RTOS 迁移实战 |
| 嵌入式 CMake 项目从零搭建 |
| GitHub 开源嵌入式 MCU 选型：GD32F303 替代 STM32F103 |
| 158 Star、18 个练习：DriverPractice 可能是最务实的 Linux 驱动入门项目 |
| 嵌入式工程师接 AI 私活的 5 个关键步骤：从报价到交付 |

---

## 行业观察 & AI 工具

| 标题 |
|------|
| Claude Code 被曝内置监控后门：你的代码和服务器信息正在被回传 |
| 147 个中国域名进了 Claude Code 的黑名单：阿里全面禁用背后的 AI 工具信任危机 |
| 36K Star、DeepSeek 官方点赞：CodeWhale 用一套"宪法"管住了 AI 编程 |
| 80K Star、TypeScript 教父出品：mattpocock/skills 为什么让工程师集体上头 |
| 15K Star、港大出品：CLI-Anything 让任意软件秒变 AI Agent 工具 |
| Google 开源 DESIGN.md：1 个文件，让 Claude Code 不再乱配你的品牌色 |

---

> **共 132 篇文章，持续更新中。**
>
> 扫码关注公众号 LabHub（微信号：OpenLabHub），进入公众号点击右上角 🔍 搜索标题阅读全文。
>
> <p align="center">
>   <img src="https://raw.githubusercontent.com/openlabhub/labhub/main/images/wechat-qrcode.jpg" width="160" alt="LabHub 公众号">
> </p>
