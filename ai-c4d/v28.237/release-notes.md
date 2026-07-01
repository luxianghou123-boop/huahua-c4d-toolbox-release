# 花花 AI 辅助工具 v28.237

更新内容：
- 修复取消描边厚度后，面板仍显示对象存在描边厚度的问题。
- 取消描边厚度时递归清理 GroupItem / CompoundPathItem / PathItem 的描边厚度状态。
- 取消后重新检测 selection 并刷新面板状态，避免旧状态残留。
- 导出 JSON 时，已取消对象不再生成 stroke thickness ring。
- 保留 v28.236 的 sourceStackIndex / sourceZOrderIndex / sourceLayerIndex / sourceLayerName / partOrder 导出字段。
- 保留 v28.235 的 inside alignment / 内孔修复。
- 不影响贴图路径、授权、CDK、检查更新逻辑。
