# VMware Aria Operations for Networks 身份认证绕过漏洞通告

报告编号：CERT-R-2023-377

更新日期：2023-08-31

## 0x01  漏洞简述

2023年08月31日，360CERT监测发现`VMware`发布了`Aria Operations for Networks`的风险通告，漏洞编号为`CVE-2023-34039`，漏洞等级：`严重`，漏洞评分：`9.8`。

VMware Aria Operations for Networks是一款网络可视性和分析工具，可以帮助管理员优化网络性能或管理和扩展各种VMware和Kubernetes部署。

## 0x02  风险等级

该漏洞的评定结果如下

| 评定方式    | 等级 |
| ----------- | ---- |
| 威胁等级    | 严重 |
| 影响面      | 广泛 |
| 攻击者价值  | 高   |
| 利用难度    | 低   |
| 360CERT评分 | 9.8  |

## 0x03  漏洞详情

### CVE-2023-34039 身份认证绕过漏洞

组件: VMware:Aria Operations for Networks

漏洞类型: 身份认证绕过

实际影响: 身份认证绕过

主要影响: 敏感数据窃取

简述: 该漏洞存在于VMware Aria Operations for Networks中，是一个身份认证绕过漏洞。由于缺乏唯一的加密密钥，具有Aria Operations for Networks网络访问权限的攻击者可以绕过SSH身份验证获取Aria Operations for Networks CLI的访问权限。

## 0x04  影响版本

### CVE-2023-34039

| 组件                                | 影响版本 | 安全版本 |
| ----------------------------------- | -------- | -------- |
| VMware:Aria Operations for Networks | < 6.11.0 | 6.11.0   |

## 0x05  修复建议

### 通用修补建议

根据`影响版本`中的信息，排查并升级到`安全版本`，或直接访问参考链接获取官方更新指南。

补丁下载地址:https://kb.vmware.com/s/article/94152