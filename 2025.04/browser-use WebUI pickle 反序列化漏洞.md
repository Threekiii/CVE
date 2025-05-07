# browser-use WebUI pickle 反序列化漏洞

## 0x01   漏洞简述

browser-use WebUI 是基于 browser-use 的 AI Agent 应用。2025 年 4 月，互联网上披露其旧版接口 update_ui_from_config 存在一个 pickle 反序列化漏洞，未经授权的远程攻击者可以利用该接口发送恶意的序列化数据，实现在服务端执行任意代码，导致服务器失陷。

## 0x02   风险等级

| 评定方式            | 等级  |
| --------------- | --- |
| 威胁等级            | 严重  |
| 影响面             | 广泛  |
| 攻击者价值           | 高   |
| 利用难度            | 低   |
| CVSS 4.0/3.x 评分 | 9.1 |

## 0x03   漏洞详情

### 披露时间

2025-04-28

### 参考链接

- https://github.com/browser-use/web-ui/commit/7fdf95edaeaf2505b36c10966b7b8d65359f1de6
- https://research.kudelskisecurity.com/2025/04/23/getting-rce-on-browser-use-web-ui-ai-agent-instances/

## 0x04   修复建议

### 通用修补建议

升级至最新版本。
