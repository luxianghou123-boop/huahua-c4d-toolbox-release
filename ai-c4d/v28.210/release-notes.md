# 花花 AI 辅助工具 v28.210

更新内容：
- 新增插件内 CDK 兑换窗口，兑换成功后弹窗提示并自动刷新授权
- 修复多次导出到同一文件夹后，C4D 导入 JSON 可能出现贴图错乱的问题
- 贴图文件名新增 JSON 文件名前缀，避免不同 JSON 导出的贴图重名
- JSON 中 texture / texturePath / textureRelPath / textureFileName 同步写入最终真实贴图路径
- 保持单一 tex 文件夹结构，不创建 exportId 子目录，不删除历史贴图
- 保留未编组对象描边厚度身份字段
- 保持导出 JSON 只弹一次保存窗口
- 保持检查更新只请求 Huahua Plugin Admin 后台服务器
