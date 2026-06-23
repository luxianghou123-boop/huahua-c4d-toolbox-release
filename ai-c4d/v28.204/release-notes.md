# 花花 AI 辅助工具 v28.204

- 接入云端 Huahua Plugin Admin 授权后台。
- 适配单账号单电脑授权规则。
- 新增 machineId 上报，同一台电脑 AI 面板和 C4D 插件后续可共用授权。
- deviceId 继续记录 AI 面板客户端，machineId 记录电脑。
- 新增 machine_replaced 处理，账号在其他电脑登录后会提示重新登录。
- 保留 session_replaced 兼容。
- session_replaced / machine_replaced 不进入离线宽限。
- 新增插件内注册账号入口。
- 授权弹窗显示电脑标识。
- 设备数量文案调整为设备记录。
- 保留导出 C4D、厚度、快捷、标注、兜底、工艺标注等原有功能。
