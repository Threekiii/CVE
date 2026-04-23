# Xinference 2.6.0-2.6.2 供应链投毒事件

## 0x01   漏洞简述

Xinference（Xorbits Inference）是一款 AI 模型部署工具。 2026 年 4 月 23 日，互联网上披露其发生供应链投毒攻击，其投毒版本（2.6.0-2.6.2）中 `__init__.py` 被插入了恶意代码，受害者安装恶意版本包后，攻击者可借此收集各类敏感信息，控制受害者服务器权限。

影响版本：

```
Xinference 2.6.0
Xinference 2.6.1
Xinference 2.6.2
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

2026-04-23

### 参考链接

- https://www.ox.security/blog/xinference-allegedly-hacked-by-teampcp-malicious-package-in-pypi/

## 0x04   修复建议

### 通用修补建议

- 若存在上述版本的 Xinference 包，请立即删除卸载
