# 【挖坑中】基于赛博空间社会模拟的意见动力学研究平台：以 Minecraft 为例

[WIP] A Research Platform for Opinion Dynamics Based on Cyberspace Social Simulation: The Case of Minecraft

*本仓库仅用作计划的设计及宣传，并不含有任何的用户信息及行为数据。*

（原始的想法纯粹是通过 Minecraft 来实现的，如果是正式写论文的话应该加一些关于 OSN 以及社交网络的介绍，然后关于 Minecraft 的一笔带过。）

## 缘起

### 萌芽

[Minecraft](https://www.minecraft.net) 作为一款自由度极高的沙盒游戏，游戏中玩家对周围有着极大的自主权，因此对于观察其中多个玩家间的行为可以相较模型仿真更能够描绘出其在现实世界~~及赛博空间~~的样貌。

自 2022 年夏天始，在哔哩哔哩的游戏分区上就掀起了或转载或发起 Minecraft 社会实验的「浪潮」。在这些不同系列的视频中，向作为旁观者的观众以及体验到了身临其境的参与者，都带来了沉浸式的角色扮演的体验。

按照知乎用户 [@炬火](https://www.zhihu.com/people/zhong-tong-di-te) 在相关问题下的回答，Minecraft 的「社会模拟」大多遵循以下的规则：

> 所有玩家同时上线下线，一命制，所有行为为玩家自发产生，鼓励玩家角色扮演，这些要素构成了所有的可游玩周目和节目视频，所有吸引玩家参与的闪光点(还有所有的类人群星闪耀时)。
>
> Source: [如何看待最近挺火的《我的世界》社会学模拟实验？ - 知乎](https://www.zhihu.com/question/516902582/answer/2558682442)

我们不难注意到，相比于原版的 Minecraft 服务器，这些模拟往往存在着向现实世界靠拢的地方，例如都存在玩家同时上下线、一命制等等的规则，也大多基于角色扮演进行。

以下是海外平台播放量相对高的作品：

>  TODO: **List some relevant YouTube channels and videos**

| 博主/项目名称 | 项目状态 | 简述 | 特点 | 相关视频资料 |
|:--: | :--: | :-- | :-- | :-- |

国内相对知名的平台/实验：

| 发起 UP 主/项目名称 | 项目状态 | 简述 | 特点 | 相关视频资料 |
|:--: | :--: | :-- | :-- | :-- |
| [巫山云玩家](https://space.bilibili.com/1405357485/channel/collectiondetail?sid=377183&ctype=0) | 暂未更新 | 发起了文明模拟的多个系列 | - | 参见该 UP 主个人空间中的视频 |
| ~~[SimMC](https://space.bilibili.com/1165243473)~~ [SimCraft官方](https://space.bilibili.com/3493143131458251) | 存续，不活跃 | SimMC 是由 UncleSn 创立的，灵感来源于 EarthMC 的生存服务器，曾顺着社会实验爆火的春风有着极高的热度（2022 年夏天） | 基于角色扮演的国家模拟的服务器 | [Minecraft服务器中的文明，战争，宗教，和历史。_bilibili_哔哩哔哩](https://www.bilibili.com/video/BV1y94y1y7gT/) |
| [宏二NordWes](https://space.bilibili.com/22890621) | 暂未更新 | xx模拟 | 更像是娱乐作品而没有社会实验的意图 | 参见该 UP 主个人空间中的视频 |

我们可以从这些系列中看出这些「社会模拟」并没有明显的学术价值，更像是在沙盒里的跑团[^roll-dice]，其一是没有采用学术研究的范式，例如定量的观测方法以及规范的流程等等，其二是并没有确定的研究课题（我们将会在下文详细讨论），更像是某种不知目的的「推演」。

[^roll-dice]: 跑团，或称 TRPG（桌上角色扮演游戏），是一种需要多个不同身份的玩家共同参与的角色扮演游戏。

### 发展

随着笔者接触了社会科学的研究视角，重新开始对这类问题生起了兴趣。

最令我感兴趣的点并非游戏中的角色扮演或是战斗中的攻防策略，而是在这种临时的社交场景下，玩家之间是如何交流信息、建立共识并成立组织的。

在之前，笔者一直尝试采用某种「建模」的方式去试图构建某一环境内的多个 Agent ，通过试图观察其行为策略来得到足以指导真实世界的客观规律。然而，由于知识储备的匮乏与知识体系的欠缺，一直没有获得一个合理的思考问题的角度与方法。这种思路并不可行的另外一个原因是真实世界的影响因素相当多，无法进行彻底完全的建模，这一方面在自然科学的研究下也有所体现，因此有「真空球形鸡」这一描述超出现实的思考的梗。

TODO: **Add some content for opinion dynamics**

## 研究对象

> 和自然科学不同的是，社会科学的研究者在其所研究的对象之中，因此研究者往往无法脱离其中。

### 社会实验？角色扮演？

### 确保事件/进程的发生（游戏节奏的控制）

#### 生产力上限

核心思路：**大规模场景需要大量来自玩家的精力。**

- 禁用物质复制
  - 不完整方块
  - 物品（末地相关） => 禁用末地
- 村民相关机制的魔改
  - => delay, delay, and delay
  - 规避刷铁机
  - 规避袭击塔
- 大规模生物
  - => 触发瘟疫 exp. 防疫工作
- 「矿透」

## 研究方法

### 游戏内的行为记录与分析工具

### 游戏外社群的记录

### 针对玩家的访谈

### 数据的量化

## 数据的存储、使用、销毁与用户隐私

## 联系我

可以选择在仓库内提 issue 或是[电邮](mailto:chestnut.roasted@outlook.com)。
