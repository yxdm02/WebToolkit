# WebToolkit

> 🤔 渗透测试信息收集阶段，被大量重复的 URL 困扰？
> 
> 😫 处理资产时，还在手动提取路径、清洗数据？
> 
> 🔍 批量处理文本时，还在反复寻找、修改脚本？
> 
> ✨ 试试这个纯前端工具集，一键处理各类文本！

一个为渗透测试人员和 Web 开发者设计的浏览器端工具集，专注于信息收集和文本处理。本工具使用纯前端技术构建，无需后端支持，保证数据处理的私密性和安全性。

## ⚡ 一键解决以下问题

- ✂️ URL去重：爬虫结果、资产清单快速去重
- 🔄 路径提取：自动分解URL路径，生成目录扫描字典
- 📝 批量处理：添加前缀、去除指定字符串
- 🌐 IP处理：CIDR转换、IP范围生成
- 🔍 Web路径提取：从JS、日志等文件中提取URL
- 💻 纯前端运行：数据处理全部在本地完成，保护数据安全

## 🎯 主要应用场景

### 渗透测试
- 信息收集阶段的 URL 整理和处理
- 资产收集过程中的路径提取和分解
- 目标 IP 地址段的生成和整理
- Web 应用测试过程中的批量路径处理
- 扫描结果的清洗和整理

### Web开发
- API 接口路径的批量处理
- 静态资源路径的提取和管理
- 开发过程中的文本批量处理
- 日志文件中的 URL 提取
- 配置文件的批量修改

## 🛠 功能特性

### 1. URL去重
- 支持按行或逗号分隔的 URL 输入
- 自动去除重复的 URL
- 支持文件导入和导出
- 适用于：
  * 爬虫结果去重
  * 扫描器输出结果整理
  * 资产清单整理
 ![image](https://github.com/user-attachments/assets/44b3e86a-7d8c-41d4-964c-449c84adc11c)


### 2. 批量加前缀
- 为多行文本批量添加指定前缀
- 支持自定义前缀内容
- 支持文件导入和导出
- 适用于：
  * 批量生成测试 URL
  * 资源路径补全
  * 域名批量添加协议头
![image](https://github.com/user-attachments/assets/d6d6f888-bf78-403a-9ab9-056d529f805d)


### 3. 路径分解
- 自动分解 URL 路径为所有子路径
- 支持处理完整 URL 和相对路径
- 结果自动去重
- 适用于：
  * 目录扫描字典生成
  * Web 应用结构分析
  * 敏感路径发现
![image](https://github.com/user-attachments/assets/b0b5b6be-7eeb-40cc-bf27-d8bf2f896e07)


### 4. 文本提取Web路径
- 从文本中提取所有 URL 和 Web 路径
- 支持 HTTP/HTTPS URL
- 支持相对路径提取
- 支持多种文件格式（.txt, .js, .html, .css）
- 适用于：
  * JavaScript 文件中的端点发现
  * 源代码中的 API 路径提取
  * 日志文件分析
  * 配置文件检查
![image](https://github.com/user-attachments/assets/6b3d52c4-6a44-45a9-8c4b-2115bc938df4)


### 5. IP地址提取
- 支持 CIDR 格式（如：192.168.0.0/16）
- 支持 IP 范围格式（如：192.168.1.1-192.168.1.254）
- 支持单个 IP 地址
- 自动验证 IP 地址格式
- 适用于：
  * 内网渗透范围确定
  * 资产梳理
  * 扫描目标生成
  * 网段划分
![image](https://github.com/user-attachments/assets/30f6b5af-aa78-4816-b30f-532ee990b669)
![image](https://github.com/user-attachments/assets/a508f2d6-0d56-415e-8d3a-4460fb5e0d7c)


### 6. 指定去除字符串
- 从文本中移除指定的字符串
- 支持批量处理
- 支持文件导入和导出
- 适用于：
  * 清理扫描结果
  * 日志文件处理
  * 批量文本清洗
![image](https://github.com/user-attachments/assets/e3592cf9-4532-4a2a-892d-4fa40665f979)


## ✨ 特色

- 🌙 深色主题界面，长期工作不伤眼
- 📱 响应式设计，支持移动设备
- 🔄 拖放文件支持，快速导入数据
- 💾 结果导出为 TXT 文件，便于后续处理
- 🚫 离线运行，保护数据安全
- 🔒 本地处理，无数据外泄风险
- ⚡ 快速处理，支持大量数据
- 🎨 直观的用户界面，操作简单

## 📖 使用方法

### 基础使用
1. 下载 HTML 文件到本地
2. 使用现代浏览器打开文件
3. 选择所需的功能标签页
4. 输入或导入要处理的数据
5. 点击相应的处理按钮
6. 查看结果并根据需要保存

### 小技巧
- 结合其他工具进行管道处理
- 配合脚本实现自动化处理
- 使用浏览器书签保存工具链接

## 💻 技术栈

- HTML5
- CSS3 (Flexbox, Media Queries)
- JavaScript (ES6+)
- 纯前端实现，无依赖

## 🔐 安全性

- 所有数据处理均在浏览器本地完成
- 不会向任何服务器发送数据
- 支持离线使用
- 无第三方依赖，代码可审计

## ⚠️ 注意事项

- 处理大量数据时建议使用 Firefox 浏览器
- 建议定期备份重要的处理结果
- 敏感数据处理请在隔离环境中进行
- 使用工具时遵守相关法律法规

## 🔄 更新计划
- [ ] 还是希望大家多提提bug
- [ ] 有issue了再更新

## 📄 License

MIT License

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来帮助改进这个工具。

## 📚 相关资源

- [OWASP信息收集指南](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/01-Information_Gathering/)
- [渗透测试方法论](https://www.pentest-standard.org/)
- [Web开发安全最佳实践](https://cheatsheetseries.owasp.org/)
