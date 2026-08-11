sed: --: No such file or directory
# Changelog

## v2.3.1 - 2026-08-11

### Added

- 同期训练的竞争—干扰—协同模型；
- 急性疲劳、恢复资源、适应信号和训练信号稀释四层判断；
- 代谢、机械和神经肌肉负荷独立记账；
- 48–72 小时局部组织竞争与适应收益 / 恢复成本决策；
- 赛事需求反推垂直容量的通用规则；
- 低强度有氧、恢复跑和完全休息的区分；
- `docs/concurrent-training-engine.md`。

### Changed

- 力量周期统一为 Build reserve → Transfer → Specific exposure → Retain；
- 明确最大力量是储备，不保证上坡经济性同步改善；
- 明确健身房动作不能替代真实下坡专项暴露；
- 将 ME 间隔、能力块长度和赛前时间窗标记为个体化起点，而非普适生理定律；
- 更新 Profile、Assessment、示例和 prompts 以记录 D−、竞争负荷和训练优先级。

### Privacy

- 仅同步通用理论；未加入 Notion 中的个人 AeT、伤病、赛事、周结构或训练目标。

## v2.2.0 - 2026-07-28

### Added

- 恢复信号主导的弹性周期；
- 5–10 天关键刺激间隔；
- 2–4 周能力块；
- 力量四层模型；
- 一般力量—最大力量—ME—维护序列；
- 主适应课与结构支持课分工；
- 个性化引擎；
- 恢复决策引擎；
- 力量周期文档；
- Runner Profile、Race Profile 和 Assessment Screen；
- 标准化示例与 prompts；
- `skill.json` 元数据。

### Changed

- 从动作菜单型力量训练升级为阶段化力量系统；
- 从固定七天执行升级为恢复信号主导；
- 从单一跑者参数升级为公开个性化 Skill；
- 示例与规则严格分离。

### Removed

- 不再将任何个人 AeT、伤病、赛事或周结构写死到公开版。
