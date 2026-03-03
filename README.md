# 🚀 JustRunMy 自动续期（GitHub Actions）

这是一个基于 GitHub Actions 的自动化脚本，用于定时登录并自动续期 JustRunMy 应用。

━━━━━━━━━━━━━━━━━━━━━━

🔐 Secrets 配置说明

| Secret 名称         | 是否必填 | 说明                                        |
|---------------------|----------|---------------------------------------------|
| JUSTRUNMY_EMAIL     | ✅ 必填  | JustRunMy 登录邮箱                          |
| JUSTRUNMY_PASSWORD  | ✅ 必填  | JustRunMy 登录密码                          |
| GOST_PROXY_TARGET   | ✅ 必填  | Gost 代理完整地址（需包含协议，如 socks5://） |

━━━━━━━━━━━━━━━━━━━━━━

📌 示例填写格式（复制下面三行，分开添加）：

JUSTRUNMY_EMAIL=abc@abc.com  
JUSTRUNMY_PASSWORD=abc123  
GOST_PROXY_TARGET=socks5://user:pass@123.456.789:1234

━━━━━━━━━━━━━━━━━━━━━━
