# Edge 密码工具箱 | Edge Password Toolbox

一个简单但实用的网页工具，用于在 Microsoft Edge（兼容 Google Chrome）和 Bitwarden 之间转换和对比 CSV 格式的密码文件。

🌐 在线使用：[https://abevol.github.io/edge-password-toolbox/](https://abevol.github.io/edge-password-toolbox/)

## 特色
- 🔑 支持 Microsoft Edge（兼容 Google Chrome）和 Bitwarden 平台的密码文件
- 🛡️ 纯前端实现，所有数据处理在本地完成，无需上传到服务器，安全可靠
- 🌍 支持中文和英文界面
- 🎨 简洁直观的用户界面
- 🔍 自动检测文件格式
- 📢 完善的信息提醒

## 功能特点

### 1. 格式转换
- 支持在 Microsoft Edge 和 Bitwarden 之间双向转换密码文件
- 保留所有重要信息（用户名、密码、URL、备注等）
- 自动处理 CSV 格式的特殊字符
- 支持批量转换
- 支持多 URI 的解析和拆分
- 显示因缺失 URI 而无法被导入到 Edge 的记录

### 2. 密码对比
- 对比两个不同平台的密码文件
- 自动检测密码不一致的记录
- 显示详细的差异信息（URL、用户名、密码等）
- 支持跨平台对比（Edge vs Bitwarden）
- 支持多 URI 的解析和拆分

## 使用说明

### 格式转换
1. 选择源文件平台格式（Microsoft Edge 或 Bitwarden）
2. 上传要转换的 CSV 密码文件
3. 点击"转换"按钮
4. 自动下载转换后的文件

### 密码对比
1. 为两个文件分别选择格式（Edge 或 Bitwarden）
2. 上传要对比的两个 CSV 文件
3. 点击"对比"按钮
4. 查看对比结果，包括：
   - 密码不匹配的记录
   - 详细的差异信息

## 隐私说明
- 所有数据处理均在浏览器本地进行
- 不会上传或存储任何密码信息
- 不会收集任何用户数据

## 技术实现
- 纯 HTML/CSS/JavaScript 实现
- 响应式设计，支持移动设备
- 使用 FileReader API 处理文件
- 支持 CSV 格式的严格解析
- 使用 JSON 集中管理多语言文本
- 基于 HTML 属性标记和本地存储实现动态多语言切换

## 浏览器兼容性
- 支持所有现代浏览器
- 推荐使用 Chrome、Firefox、Edge 最新版本
- 支持 IE11（基本功能）

## 开源协议
MIT License

## 贡献指南
欢迎提交 Issue 和 Pull Request 来帮助改进这个工具。

## 致谢
感谢所有为这个项目提供反馈和建议的用户。