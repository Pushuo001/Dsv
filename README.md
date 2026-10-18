# DSV

DSV（DualSense Video Haptics）是一个开放式项目，目标是让本地视频观影体验更具沉浸感。我们希望通过为本地视频创建“触觉时间线”，让 DualSense 手柄在播放电影、动画、短片、演示视频时同步输出高保真振动反馈，让视觉体验更有冲击力和情绪张力。

DSV 的核心愿景是：让视觉更加生动。

## 项目目标

- 为本地视频生成和共享 haptic timeline
- 使用音频指纹/文件指纹来自动匹配视频与对应时间线
- 在本地播放器中按时间触发 DualSense 的震动、模式与 Trigger 反馈
- 让社区共同维护一套轻量、开放、可扩展的触觉数据生态

## 项目愿景

我们希望不是做“AI 随机生成反馈”，而是做“可编辑、可分享、可复用的精细触觉时序”。

就像游戏里有精心设计的触觉反馈一样：
- 爆炸时震感更强
- 低沉对话时轻微震动
- 激烈动作段中强调脉冲感
- 场景切换时通过 trigger / haptics 做情绪标记

## 这是一个什么样的项目？

这是一个面向社区协作的开源项目，分为几部分：

- 作者端：为视频创作 haptic timeline
- 匹配端：用文件哈希/音频指纹匹配本地视频和对应配置
- 播放端：本地播放器在播放时发送 haptics 指令到 DualSense
- 社区端：共享 timeline、反馈、改进和测试样本

我们希望做一个“本地视频 + 触觉增强”的生态，而不是为了简单试一试的 demo。

## 当前状态

项目目前处于早期规划和社区建设阶段：

- 目标：建立可运行的早期 PoC
- 方向：Windows + 本地视频 + DualSense + haptic timeline
- 优先级：开源、可测试、可扩展、可协作

## 为什么做这个项目？

很多视频观看体验都是“听 + 看”，但很少有“感受”。

如果你在看电影时，爆炸、冲突、气流、打斗、激烈音乐都能在手柄上有对应反馈，那么视频内容会更具临场感和情绪张力。

DSV 的目标并不是替代游戏，而是让视觉体验“更生动”。

## 项目路线图

### Phase 1：基础社区与 PoC

- 建立项目结构和贡献流程
- 明确 haptic timeline 数据格式
- 建立示例 timeline 与 demo
- 实现最基础的本地播放和手柄触发

### Phase 2：匹配与分享

- 根据文件哈希、音频指纹自动匹配对应时间线
- 做作者上传/下载流程
- 优化 timeline 对齐和 seek / pause / resume

### Phase 3：高保真与扩展

- 支持更细粒度的 haptics 事件
- 支持 Trigger / HD Haptics 的更完整输出
- 改进编辑器体验和本地预览

### Phase 4：社区协作生态

- 提供 timeline marketplace / community list
- 提供 dashboard 与审核机制
- 支持可持续的开源贡献和维护

## 安全与合规

本项目要求且鼓励参与者遵守合规要求：

- 不上传或分发受版权保护的视频内容本体
- 不鼓励违法盗版或绕过 DRM 的行为
- 仅支持用户本地合法拥有的媒体文件
- 在上传时间线时明确权属声明

更多内容见 [SECURITY.md](SECURITY.md) 和 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 参与方式

如果你有兴趣参与，欢迎加入：

- 代码开发（Windows / HID / 播放器集成 / Python / Node）
- 设计与编辑器体验
- 音频与信号处理
- 测试与文档撰写
- 社区运营与翻译
- 触觉时间线设计与调校

请先阅读：

- [CONTRIBUTING.md](CONTRIBUTING.md)
- [docs/ROADMAP.md](docs/ROADMAP.md)

## 贡献者

欢迎所有愿意为项目做出贡献的朋友。发起人与维护者会在 README 和项目页中记录重要贡献者，以感谢所有参与者。

## 许可证

本项目采用 MIT License。详情请见 [LICENSE](LICENSE)。

## 公开说明

本项目旨在提升观影体验，并不用于破坏、绕过或绕过平台安全机制。项目要求所有参与者遵守当地法律与平台规则，并尊重版权所有者与知识产权。

## 接下来

如果你愿意参与，请：

1. 阅读 [CONTRIBUTING.md](CONTRIBUTING.md)
2. 查看 [docs/ROADMAP.md](docs/ROADMAP.md)
3. 在 GitHub 上提交一个 issue 或提出想法
4. 如果你没有代码经验，也欢迎帮助测试、文档、设计和社区推广

---

DSV is an open project aimed at making local video playback more immersive. The goal is to create haptic timelines for videos and use them to drive DualSense vibration patterns, making movies, animations, clips, and other media feel more vivid and emotional.

The project is designed around community-driven development and open collaboration.

For the English version of the contribution guide and project context, see [CONTRIBUTING.md](CONTRIBUTING.md).

