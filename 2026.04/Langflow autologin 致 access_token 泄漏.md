# Langflow autologin 致 access_token 泄漏

## 0x01   漏洞简述

Langflow 是一款基于可视化界面的低代码/无代码开发工具，专为构建大模型（LLM）应用而设计。若 AUTO_LOGIN 设置为 True，攻击者可构造请利用 /api/v1/auto_login 接口获取 access_token，并利用 access_token 调用 Langflow 后台相关接口，执行任意操作，甚至可导致代码执行。

## 0x02   风险等级

| 评定方式            | 等级  |
| --------------- | --- |
| 威胁等级            | 严重  |
| 影响面             | 广泛  |
| 攻击者价值           | 高   |
| 利用难度            | 低   |
| CVSS 4.0/3.x 评分 | 9.9 |

## 0x03   漏洞详情

### 披露时间

2026-04-10

### 参考链接

- https://docs.langflow.org/api-keys-and-authentication

## 0x04   修复建议

### 通用修补建议

- 设置 AUTO_LOGIN 为 False。
- 利用安全组设置 Langflow 设置其仅对可信地址开放。
