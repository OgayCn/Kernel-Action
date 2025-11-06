### 自动构建6.1-LTS分支内核

> 本仓库仅支持 6.1 内核的 GKI 设备，[在此](https://source.android.com/docs/core/architecture/kernel/gki-release-builds?hl=zh-cn)查看您的设备是否支持

### 下载刷入
- 可以 [点击此处](https://github.com/OgayCn/GKI-Kernel-Action/releases) 下载本仓库编译的资源
- 下载Ak3.zip文件，然后使用 [SukiSU Ultra](https://github.com/ShirkNeko/SukiSU-Ultra) 刷入

### 支持
| 功能 | 说明 |
| --- | --- |
| [SukiSU Ultra](https://github.com/ShirkNeko/SukiSU-Ultra) | 一个 Android 上基于内核的 root 方案，由 [`tiann/KernelSU`](https://github.com/tiann/KernelSU) 分叉而来，添加了一些有趣的变更。 |
| [SUSFS-Patch](https://gitlab.com/simonpunk/susfs4ksu) | 一个隐藏 KernelSU 和安装/挂载在用户空间上KSU/Magisk模块的内核补丁。 |
| [BBG防格机](https://github.com/vc-teahouse/Baseband-guard) | 一个面向 Android 内核的轻量级 **LSM模块（Linux Security Module）**，用于从内核层面阻止对关键分区/设备节点的非法写入，降低基带、引导链等关键组件被恶意/误操作篡改的风险 |
| [BBR算法](https://blog.thinkin.top/archives/ke-pu-bbrdao-di-shi-shi-me) | 一种由Google开发的TCP拥塞控制算法，具有更好的网络吞吐量、更低的延迟和更少的拥塞丢包等优点。 |
| [Wireguard](https://zh.wikipedia.org/wiki/WireGuard) | 一种实现加密虚拟专用网络(VPN) 的通信协议，其设计目标是易于使用、高速性能和低攻击面。可以通过不同网段，不同地区的实现异地组网，通过UDP传递流量，高效稳定。 |
| [Mi-Patch](https://github.com/OgayCn/Kernel-Patch) | 修复米系手机使用 Google 的 GKI-LTS 最新分支编译带来的严重问题（如：屏幕闪烁、WIFI/USB网络共享无法启用 等问题）的内核补丁 |
| [Clang 22](https://github.com/ZyCromerZ/Clang) | 使用 Zyc Clang22编译器编译 |
| [其他功能](https://github.com/OgayCn/Kernel-Action/releases) | 更多支持的功能请看 Releases 发布详情 |