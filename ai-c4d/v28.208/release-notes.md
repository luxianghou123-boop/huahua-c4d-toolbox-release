花花 AI 辅助工具 v28.208

更新内容：
- 修复导出 C4D JSON 时重复弹出选择路径的问题
- 导出时只保留一次 JSON 保存窗口，贴图目录自动使用同级 tex 文件夹
- 修复未编组对象同时设置填充厚度和描边厚度后，导入 C4D 被错误合并的问题
- JSON 导出新增 objectId / itemId / partType / groupId / groupPath / groupKey / importIndex
- 未编组对象不再共享默认 group
- 同一原始对象的 fill / stroke 共享 objectId，并通过 partType 区分
- 真实 AI 编组对象仍允许按 group 合并
- 保持 AI 面板检查更新只请求后台服务器

Windows 安装器说明：
- 检测 Illustrator.exe 是否运行
- 自动清理旧用户 CEP 目录
- 删除失败时自动重命名旧目录
- 安装到 %APPDATA%\Adobe\CEP\extensions\HH_AI_C4D_CEP
- 安装后校验 HH_VERSION.txt
- 写入桌面安装日志 huahua_ai_c4d_install_log.txt
