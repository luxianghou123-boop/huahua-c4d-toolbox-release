# 花花 AI 辅助工具 v28.236

更新内容：
- 新增 AI 原始层级导出字段 sourceStackIndex / sourceZOrderIndex / sourceLayerIndex / sourceLayerName / partOrder。
- 修复描边厚度对象拆分为 fill / stroke ring 后原始前后层级丢失的问题。
- stroke thickness 拆分对象继承同一个源对象层级，最终 JSON 按源层级排序并重写连续 importIndex。
- 避免下层底板在 C4D 中遮挡上层图形。
- 保留 v28.235 的 inside alignment fallback 修复。
- 保留 v28.232 本地 inner 映射、v28.233 递归读取、v28.234 unknown 不参与 center 投票逻辑。
- 不修改 stroke ring 几何、C4D 分组字段、贴图路径、授权、CDK 和检查更新逻辑。
