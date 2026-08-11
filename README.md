sed: --: No such file or directory
# Trail Running Training Decision Skill

**v2.3.1｜同期训练与适应成本管理版**

一个面向越野跑和超长距离跑者的 AI 训练决策 Skill。它不是固定课表，而是：

> 先收集跑者资料 → 判断阶段与风险 → 生成个性化计划 → 根据恢复信号动态调整。

## 核心模型

> 越野跑表现 = 代谢能力 × 力量能力 × 机械承载 × 技术经济性 × 疲劳韧性 × 补给兑现 × 心理执行

日常使用三重门：

1. 代谢门：AeT、CS、阈值、VO₂max、热适应；
2. 机械门：最大力量、ME、下坡离心、足踝和单腿稳定；
3. 执行门：补给纪律、前半程克制、走跑切换和疲劳后决策。

## v2.3.1 升级

- 7 天结构只是生活容器；
- 关键刺激采用 5–10 天弹性间隔；
- 使用 2–4 周能力块；
- 新增同期训练的竞争—干扰—协同模型与四层干扰判断；
- 代谢、机械和神经肌肉负荷独立记账；
- 力量遵循“Build reserve → Transfer → Specific exposure → Retain”；
- 明确力量储备不等于上坡经济性，真实下坡暴露不可替代；
- 区分低强度有氧、恢复跑与完全休息；
- 使用适应收益 / 恢复成本和 48–72 小时局部组织竞争进行每日决策；
- 主适应课与结构支持课分工；
- 提供个性化、恢复、力量周期和同期训练四个引擎；
- 提供 Runner Profile、Race Profile 和 Assessment Screen。

## 使用顺序

1. `SKILL.md`
2. `docs/personalization-engine.md`
3. `docs/recovery-decision-engine.md`
4. `docs/strength-periodization.md`
5. `docs/concurrent-training-engine.md`
6. `templates/runner-profile-template.md`
7. `templates/race-profile-template.md`
8. `templates/assessment-screen.md`

## 安装提示语

```text
请读取本仓库的 SKILL.md、docs 和 templates。
把 SKILL.md 作为总规则，把 docs 作为决策引擎。
在我填写 Runner Profile、Race Profile 和 Assessment Screen 之前，
不要给出完整高阶训练计划，也不要把 examples 当成默认课表。
```

## 安全边界

本项目不替代医生、物理治疗师或专业教练。出现胸痛、晕厥、发热、走路疼痛、疼痛改变跑姿、疑似应力性损伤或神经症状时，应停止高负荷训练并寻求专业帮助。

## License

CC BY-NC 4.0。
