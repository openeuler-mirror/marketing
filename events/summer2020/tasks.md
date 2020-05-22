### openEuler 社区任务列表

#### [为 openEuler 添加 Xfce 桌面环境并能够运行在树莓派 4B 上](https://gitee.com/openeuler/marketing/issues/I1H8G3)

树莓派（英语：Raspberry Pi）是基于 Linux 的单片机电脑，目的是以低价硬件及自由软件促进学校的基本计算机科学教育。openEuler 树莓派版本目前没有桌面环境。本项目的目标是为树莓派添加桌面支持，即适配桌面环境 Xfce 到 openEuler 树莓派 4B。

任务链接 https://gitee.com/openeuler/marketing/issues/I1H8G3

#### [精简 openEuler 的树莓派 4B 镜像体积小于 500 MiB](https://gitee.com/openeuler/marketing/issues/I1H8H9)

树莓派（英语：Raspberry Pi）是基于 Linux 的单片机电脑，目的是以低价硬件及自由软件促进学校的基本计算机科学教育。树莓派需要刷写文件系统镜像来实现启动，镜像文件常常都较大，不利于快速分发和安装。本项目目标是为制作压缩前小于 500 MiB 的 openEuler 树莓派 4B 镜像，并能够通过 DNF 或 YUM等安装软件源中更多的软件进来。镜像尽可能小。

任务链接 https://gitee.com/openeuler/marketing/issues/I1H8H9

#### [为 openEuler 树莓派 4B 镜像提供 UEFI 启动支持](https://gitee.com/openeuler/marketing/issues/I1H8HV)

树莓派（英语：Raspberry Pi）是基于 Linux 的单片机电脑，目的是以低价硬件及自由软件促进学校的基本计算机科学教育。为了降低成本，树莓派省去了传统计算机用来存储引导加载程序的板载存储器(BIOS), 直接把引导程序放在了SD卡中。目前树莓派 Pi 4 引入了 UEFI，不过目前处于 EXPERIMENTAL 状态。本项目目标是为树莓派引入 UEFI Firmware 来支持 UEFI 启动 openEuler 树莓派 4B。

任务链接 https://gitee.com/openeuler/marketing/issues/I1H8HV

#### [Build openEuler from scratch](https://gitee.com/openeuler/marketing/issues/I1HAXJ)

借鉴 Linux From Scratch，开发一套工具，从零构建openEuler，可以支持新架构。一个可能的建议是，从openEuler x86_64 构建 i686版本。目标：交叉构建一个新架构i686的rootfs，该rootfs是由200-300+软件包的rpms组成。基于这些rpms，可以在koji或obs上继续构建其他上层软件包。最终构建出openEuler所有支持的软件。

任务链接 https://gitee.com/openeuler/marketing/issues/I1HAXJ