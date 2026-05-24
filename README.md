# 🔒 Lockbox · 全算法加密工具箱

<div align="center">

![许可](https://img.shields.io/badge/许可-MIT-30d158?style=flat-square)
![技术栈](https://img.shields.io/badge/技术栈-Web%20Crypto%20API-ffb900?style=flat-square)
![平台](https://img.shields.io/badge/平台-Web-0078d7?style=flat-square)

**一个纯浏览器端运行的加密工具 · 60+种算法 · 支持GB级大文件 · 流式处理**

[🌐 在线体验](https://lockbox-3mt.pages.dev) · 
[⭐ Star支持](https://github.com/jia-sbg/lockbox)

</div>

---

## ✨ 特性亮点

| 类别 | 功能 |
|------|------|
| 🔐 **海量算法** | 60+种加密算法，涵盖古典密码、现代对称加密、哈希、编码格式 |
| 📁 **文件加密** | 支持GB级大文件流式处理，不卡顿不崩溃 |
| 🌍 **双语界面** | 中文/英文一键切换，国际化支持 |
| 💾 **纯本地运行** | 所有运算在浏览器本地执行，数据不上传任何服务器 |
| 🎨 **现代密码学** | 使用Web Crypto API实现AES-GCM、ChaCha20等顶级算法 |
| 📋 **一键操作** | 复制结果、清空输入、下载文件，操作便捷 |

## 🎯 快速开始

### 在线体验
- **Cloudflare Pages**：[https://lockbox-3mt.pages.dev](https://lockbox-3mt.pages.dev)
- **GitHub Pages**：[https://jia-sbg.github.io/lockbox](https://jia-sbg.github.io/lockbox)

### 本地运行
```bash
# 克隆仓库
git clone https://github.com/jia-sbg/lockbox.git

# 使用任意HTTP服务器启动（如Python）
python -m http.server 8080

# 或使用VS Code Live Server
```

🛠️ 支持的算法

原创中文加密

· 中文加密 · 中文加密Plus

古典密码

· 凯撒密码 · 维吉尼亚 · Autokey · Beaufort · ROT13 · ROT47
· Atbash · 栅栏密码 · 列换位 · Playfair · Polybius方阵
· Hill (2x2) · ADFGVX · Bifid · Four-square

简单加密

· XOR 异或 · RC4 · RC4-drop

编码格式

· Base64/Base64URL · Base32/Base32Hex · Base58 · Base85 · Base45
· URL编码 · Hex十六进制 · 二进制 · 摩斯电码 · UUencode

哈希算法（不可逆）

· MD5 · SHA-1 · SHA-256 · SHA-384 · SHA-512
· SHA3-256 · SHA3-512 · CRC32 · HMAC-SHA256 · HMAC-SHA512

现代对称加密

· AES-128/192/256-GCM · AES-256-CBC · AES-256-CTR
· ChaCha20 · Blowfish · Twofish · AES+凯撒

非对称加密

· RSA+AES · RSA+ECDSA

📖 使用方法

文字加密/解密

1. 选择所需加密算法
2. 输入密码（如算法需要）
3. 在输入框输入明文或密文
4. 点击「加密」或「解密」按钮
5. 结果自动显示在输出区域，可一键复制

文件加密/解密

1. 切换至「文件加密」模式
2. 选择算法并输入密码
3. 上传需要处理的文件
4. 点击加密/解密，等待处理完成
5. 下载结果文件

🔒 安全说明

· 纯本地运算：所有加密解密均在您自己的浏览器中完成，不会上传任何数据到服务器
· 现代密码学：AES-GCM、ChaCha20等算法使用浏览器原生Web Crypto API实现，安全性有保障
· 古典密码：仅用于教学和娱乐目的，不建议用于保护真正敏感的信息
· 密钥管理：请妥善保管您的密码/密钥，丢失后将无法恢复数据
· 临时存储：页面关闭后，所有输入数据将被清除，不留痕迹

🏗️ 技术架构

```
┌─────────────────────────────────────────────────┐
│                 Lockbox 主界面                   │
├─────────────────────────────────────────────────┤
│  算法选择器（60+种算法分类展示）                  │
│  输入模式切换（文字/文件）                        │
├─────────────────────────────────────────────────┤
│              加密/解密引擎                       │
│  ┌───────────────────────────────────────────┐  │
│  │  古典密码（纯JS实现）                      │  │
│  │  现代密码（Web Crypto API）                │  │
│  │  哈希算法（SubtleCrypto）                  │  │
│  │  编码转换（内置函数）                      │  │
│  └───────────────────────────────────────────┘  │
├─────────────────────────────────────────────────┤
│            大文件流式处理模块                    │
│  FileReader + 分块读取，支持GB级文件             │
└─────────────────────────────────────────────────┘
```

📁 项目结构

```
lockbox/
├── index.html          # 单文件完整系统
└── README.md           # 项目说明
```

🤝 参与贡献

1. Fork 本仓库
2. 创建特性分支 (git checkout -b feature/AmazingFeature)
3. 提交更改 (git commit -m 'Add some AmazingFeature')
4. 推送到分支 (git push origin feature/AmazingFeature)
5. 提交 Pull Request

📜 声明

· AI辅助开发：本项目由多个AI协助完成
· 原创声明：代码和设计均为独立原创
· 开源许可：MIT License

👤 作者

· GitHub：jia-sbg
· B站：GoYi-1（欢迎关注！）

<div align="center">

如果觉得不错，别忘了点个Star ⭐

🔗 GitHub仓库 · 
🎬 B站主页

DeepSeek生成的😋

</div>
```
