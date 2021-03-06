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

### 2.3 openEuler 导师沟通指导

#### 回复第一封联系邮件的注意事项

1. 要求学生提供学校、院系、专业、年级等基本信息。
2. 要求学生提供基本简历信息，包括但不限于在实验室从事过的项目经验、实习期间的项目经验、竞赛证书、开源项目参与经历等内容。
3. 尽量要求学生提供 Github/Gitee 帐号。
4. 尽量要求学生提供一些代码示例证明其开发能力。注意不要让学生通过邮件发送代码，而是要求他们发布到 Github/Gitee 等代码托管网站。
5. 引导学生通过邮件和导师交流。
6. 引导学生注册邮件列表，通过邮件列表的方式公开交流。
7. 要求学生按照 https://isrc.iscas.ac.cn/summer2020/help/student.html#%E5%AD%A6%E7%94%9F%E5%A6%82%E4%BD%95%E6%8A%A5%E5%90%8D 链接指引进行报名。导师是在报名结束后，选择一名报名的学生参与项目开发。不限制学生报名多个项目，也不限制一个项目有多个学生报名。

#### 沟通中的其它问题

1. 负责对学生提出的关于项目细节问题的解答，在学生报名截止日期之间应积极解答学生针对项目提出的问题。
   - 提供一些相关的资料，回复后资料应该添加到任务的 Issue 中，提升任务内容的明确性。
   - 针对问题的解答在 Issue 中归档。
   - 针对问题细化任务的描述、验收等部分，尤其是给出明确的完成标准，并更新在 Issue 中。
   - 对于任务中描述中存在歧义的地方尽快修改，**请勿修改任务标题** 。
2. 在学生准备项目方案期间，导师应给予积极的方向性的指导和相关技术材料的分享，协助学生制定更具有可行性的方案以及合理的项目开发计划。
   - 对于候选学生提供一个解决问题的思路，思路不要求完全正确，但是方向是正确。
   - 引导学生通过资料的学习，更新技术方案；对于技术方案的选择要引导学生
   - 对于完成任务需要提供一个时间计划。
   - 对于解决方案要求包含测试的方案。
   - 对于解决方案要求包含文档的规划。
3. 指导学生如何成为社区的一份子，指导学生使用社区常用的沟通工具（电子邮箱、邮件列表等）。
4. 指导学生遵循社区的规范，使用社区的代码管理平台以及其他工具。
   - 对于目前在 openEuler 组织下没有仓库承载的任务，在活动组织方的提供的代码托管平台进行开发。
5. 与学生进行积极有效的沟通，适当通过问题的方式让学生独立思考解决方式。
6. 避免直接告诉学生解决答案，通过方向性的指引来引导学生。
7. 项目开发期间，保持与学生的定期沟通，保持持续了解到学生的开发进度，组委会建议应至少保证每周一到两次的沟通。
   - 社区会安排组织会议保证学生和导师之间的沟通。
8. 应顾及到学生的专业水平和年龄，友好耐心的保持沟通，鼓励学生独立并积极的开展开发工作。
