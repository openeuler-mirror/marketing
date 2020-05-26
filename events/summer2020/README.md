# 开源软件供应链点亮计划 - 暑期 2020 

[开源供应链点亮计划 - 暑期 2020](https://isrc.iscas.ac.cn/summer2020)是由中科院软件所和 [openEuler](https://openeuler.org) 社区共同举办的一项面向高校学生的暑期活动，旨在鼓励在校学生积极参与开源软件的开发维护，促进国内优秀开源软件社区的蓬勃发展。

从即日起 openEuler 社区通过[开源供应链点亮计划 - 暑期 2020](https://isrc.iscas.ac.cn/summer2020)活动发布开发任务，在活动过程中有对开发任务感兴趣的在校学生会通过社区 Issue / 邮件等方式和发布任务的导师进行沟通。 2020 年 6 月 30 日导师公布选中参与任务开发的学生，从 7 月 1 日开始到 9 月 30 日之间进行为期三个月的开发，在这个过程中导师对学生进行多种形式的辅导，帮助学生完成开发任务。

更多活动介绍
1. https://docs.google.com/presentation/d/1XtMfT6XLLMw4yajz0M_Gi9WI71yk-rhWqx3xcT1q5kU
2. https://isrc.iscas.ac.cn/summer2020
3. https://openeuler.org/zh/events/20200607.html

## 1. [openEuler 社区任务列表](tasks.md)


## 2. openEuler 社区任务提交方式

openEuler 社区的开发任务在 Marketing SIG 仓库通过 [Issue](https://gitee.com/openeuler/marketing/issues) 的方式提交。如果有额外的文件需要补充，可以使用 [Issue](https://gitee.com/openeuler/marketing/issues) 的上传附件功能补充添加。

- [Issue 类型] _暑期2020_
- [负责人] 增加 _genedna_ 和 _allesgute_ 为协作者
- [标签] _summer2020__
- [计划开始日期] 2020-07-01
- [计划完成日期] 2020-09-30
- [标题] 和任务标题相同
- [内容] 推荐使用以下任务模板

### 2.1 openEuler 社区任务模板

_标题_ <同 Issue 标题，标题尽量能够一句话概括题目的内容>

_描述_ <如果描述中有代码请使用 Markdown 的代码高亮格式增加可读性；对于任务描述尽量增加背景信息或需求信息，以便于和学生沟通中明确需求>

_难度_ <可以选择难、中、易三个级别描述，对于级别难度原则由导师自己决定，但请参考高校学生的能力>

_导师_ <请使用 [genedna](https://gitee.com/genedna) 的格式填写导师在 Gitee ID>

_联系方式_ <必填邮箱，推荐学生和导师通过邮件沟通，同时建议学生和导师通过 openEuler 的邮件列表沟通，并同时参加相应 SIG 的周会>

_产出标准_ <产出标准需要能够衡量，建议以任务完成合入到仓库主线为最终是否完成的标准>

_技术要求_ <列出完成任务的需要基本技能>

_相关项目_ <列出依赖项目的链接或者代码仓库地址>

_相关资料_ <罗列能提供的参考资料链接>


### 2.2 openEuler 社区任务示例

_标题_ 为 openEuler 添加 Xfce 桌面环境并能够运行在树莓派 4B 上
 
_描述_ 树莓派（英语：Raspberry Pi）是基于 Linux 的单片机电脑，目的是以低价硬件及自由软件促进学校的基本计算机科学教育。openEuler 树莓派版本目前没有桌面环境。本项目的目标是为树莓派添加桌面支持，即适配桌面环境 Xfce 到 openEuler 树莓派 4B。
 
_难度_ 高
 
_导师_ [@allesgute](https://gitee.com/allesgute)
 
_联系方式_ qusheng@iscas.ac.cn
 
_产出标准_
1. 小于 200 MB 的树莓派镜像，该镜像可刷写在树莓派 Pi 4 上
2. 镜像中版本号信息为 openEuler 20.03
3. 镜像支持 DNF 安装 openEuler 软件源中的软件
 
_技术要求_
1. openEuler
2. 基本的 Linux 命令
3. DNF/RPM 包管理
4. 具备一种脚本语言，如 Python、Bash script 等
5. 压缩算法
 
_相关项目_
1. https://gitee.com/openeuler/raspberrypi
2. https://gitee.com/openeuler/raspberrypi-kernel

_相关资料_
1. https://www.raspberrypi.org