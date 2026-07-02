# 花花 AI C4D 工具 v28.238

更新内容：
- 修复导出完成后 Illustrator 偶发进入假卡死状态，导致无法框选 / 无法正常选择对象的问题。
- 导出流程增加统一 cleanup，恢复 userInteractionLevel、selection、redraw 和前端 exporting 状态。
- 导出成功、失败或取消保存窗口后，都会恢复 Illustrator 交互状态。
- 保留 v28.237 的取消描边厚度状态修复。
- 保留 v28.236 的 AI 层级导出字段和 v28.235 的描边内孔修复。
- 不影响贴图路径、授权、CDK、检查更新逻辑。
