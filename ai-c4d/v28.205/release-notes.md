花花 AI 辅助工具 v28.205

更新内容：
- AI 面板检查更新改为只请求 Huahua Plugin Admin 后台服务器。
- 不再直接访问 GitHub update.json。
- 不再直接访问 GitHub Release 下载地址。
- 下载地址由后台返回，支持服务器镜像和备用下载。
- AI 面板只接收后台 published 版本，不接收 staged 待发布版本。
- 保留授权、注册、machineId、machine_replaced、session_replaced 等规则。
- 保留导出 C4D、厚度、快捷、标注、兜底、工艺标注等原有功能。

Windows 安装器：
- 保留强制安装器逻辑。
- 安装前检测 Illustrator.exe。
- 自动删除旧用户 CEP 目录。
- 删除失败时重命名旧目录。
- 安装到 %APPDATA%\Adobe\CEP\extensions\HH_AI_C4D_CEP。
- 安装后校验 HH_VERSION.txt / v28.205。
- 写安装日志到桌面 huahua_ai_c4d_install_log.txt。
