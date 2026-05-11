# PyTorch Lightning 2.6.2 & 2.6.3 供应链投毒事件

## 0x01   漏洞简述

PyTorch Lightning 是一款 AI 模型部署工具。 2026 年 4 月 30 日，互联网上披露其发生供应链投毒攻击，其投毒版本（2.6.2、2.6.3）中被插入了如 routerruntime.js 等恶意代码，受害者安装恶意版本包后，攻击者可借此收集各类敏感信息，控制受害者服务器权限。

影响版本：

```
PyTorch Lightning 2.6.2
PyTorch Lightning 2.6.3
```

## 0x02   风险等级

| 评定方式            | 等级  |
| --------------- | --- |
| 威胁等级            | 高危  |
| 影响面             | 广泛  |
| 攻击者价值           | 高   |
| 利用难度            | 低   |
| CVSS 4.0/3.x 评分 | 8.1 |

## 0x03   漏洞详情

### 披露时间

2026-04-30

### 参考链接

- https://semgrep.dev/blog/2026/malicious-dependency-in-pytorch-lightning-used-for-ai-training/

## 0x04   修复建议

### 通用修补建议

- 若存在上述版本的 PyTorch Lightning 包，请立即删除卸载
