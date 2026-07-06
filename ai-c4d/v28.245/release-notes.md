# 花花智能建模-AI端 v28.245

- 修复单独导出贴图时，如果选择对象带有描边厚度，会额外导出 JSON 文件的问题。
- mode=images 现在只导出 PNG / JPG 图片，不再弹 JSON 保存窗口，也不写出 C4D JSON。
- 完整 JSON 导出逻辑保持不变，仍然支持 JSON + 同级 tex 目录。
- 保留 v28.244 的贴图导出 undefined 修复。
- 保留 v28.243 的 fillColor / strokeColor 绑定修复。
- 保留 v28.242 的多颜色文字导出修复。
- 保留 v28.241 的多描边色 stroke ring 修复。
