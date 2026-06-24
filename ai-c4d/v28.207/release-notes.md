花花 AI 辅助工具 v28.207

更新内容：
- 修复未编组对象同时设置填充厚度和描边厚度后，导入 C4D 被错误合并的问题。
- JSON 导出新增 objectId / itemId / partType / groupId / groupPath / groupKey / importIndex。
- 未编组对象不再共享默认 group。
- 同一原始对象的 fill / stroke 共享 objectId，并通过 partType 区分。
- 不同原始对象即使颜色、填充厚度、描边厚度相同，也会导出不同 objectId。
- 真实 AI 编组对象仍允许按 group 合并。
- 保留 craftType / craftParams、兜底标记、导出 C4D、授权、注册、machineId、machine_replaced、session_replaced 逻辑。
- 保持 AI 面板检查更新只请求 Huahua Plugin Admin 后台。

Windows 安装器：
- 保留强制安装器逻辑。
- 安装前检测 Illustrator.exe。
- 自动删除旧用户 CEP 目录。
- 删除失败时重命名旧目录。
- 安装到 %APPDATA%\Adobe\CEP\extensions\HH_AI_C4D_CEP。
- 安装后校验 HH_VERSION.txt / v28.207。
- 写安装日志到桌面 huahua_ai_c4d_install_log.txt。
