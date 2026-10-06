# iPhone Automation Downloads

这是 `iphone-automation-agent` 的公开下载仓库，只存放经过检查、允许公开的测试页面和快捷指令文件。

公开下载页：<https://er18-w.github.io/iphone-automation-downloads/>

## EXP-0002：G2 日期流程测试

请按 **V1 → V2 → V1 回退** 的顺序在目标 iPhone 上测试。

### V1

- 文件：`STG-G2-DATE-V1.shortcut`
- 大小：22,296 字节
- SHA-256：`8D8279D30BCDD10AF84D66E18885CBC80A1E6A2368C474FDB0266D18B2892291`
- 预期：显示“当前时间：”和当前日期时间。

### V2

- 文件：`STG-G2-DATE-V2.shortcut`
- 大小：22,308 字节
- SHA-256：`A5A89DF376FCDFF22B042CC83038484F34CF226A65606F3B280F49E2B56EDEEF`
- 预期：前缀变为“现在是：”，日期使用中文格式。

## 已通过的 G1 固定测试

- 文件：`STG-SMOKE-001.shortcut`
- 大小：21,911 字节
- SHA-256：`C7D5BC070BF5FDB51DA9158B650FF5F65B187A988BCD81B9C86EE094D1DA454C`

## 公开安全规则

- 不上传账号、密码、令牌、个人数据或私人服务地址。
- 每次发布前核对文件大小和 SHA-256。
- GitHub Pages 只负责静态页面与文件下载，不代表真机新建、修改或回退已经通过验证。
