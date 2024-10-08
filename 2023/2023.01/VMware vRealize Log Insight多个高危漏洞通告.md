# VMware vRealize Log Insight多个高危漏洞通告

报告编号：B6-2023-013001

更新日期：2023-01-30

## 0x01  漏洞简述

2023年01月30日，360CERT监测发现`VMware官方`发布了`VMware vRealize Log Insight`的风险通告，漏洞编号为`CVE-2022-31706,CVE-2022-31704，CVE-2022-31710，CVE-2022-31711`，漏洞等级：`高危`，漏洞评分：`9.8`。

vRealize Log lnsight 提供了高度可扩展的异构日志管理功能，它具有多个可在其中执行操作的直观仪表盘、完善的分析功能和范围更广的第三方延展性。VMware vRealize Log Insight 提供集中式日志管理、深度运维可见性和智能分析 (sysin)，从基础架构到跨本地部署和私有云环境的应用，都能提供更好的故障排除和更高的安全性。

## 0x02  风险等级

该漏洞的评定结果如下

| 评定方式    | 等级 |
| ----------- | ---- |
| 威胁等级    | 高危 |
| 影响面      | 广泛 |
| 攻击者价值  | 高   |
| 利用难度    | 低   |
| 360CERT评分 | 9.8  |

## 0x03  漏洞详情

### CVE-2022-31706: VMware vRealize Log Insight目录遍历漏洞

CVE: CVE-2022-31706

组件: vRealize Log Insight

漏洞类型: 目录遍历

影响: 代码执行

简述: 该漏洞存在于vRealize Log Insight中，是一个目录遍历漏洞。未经身份验证的攻击者可以通过组合利用CVE-2022-31706、CVE-2022-31704将恶意文件写入服务器，从而导致远程代码执行。

### CVE-2022-31704: VMware vRealize Log Insight访问控制漏洞

CVE: CVE-2022-31704

组件: vRealize Log Insight

漏洞类型: 代码执行

影响: 服务器接管

简述: 该漏洞存在于vRealize Log Insight中，是一个访问控制漏洞。未经身份验证的攻击者可以通过组合利用CVE-2022-31706、CVE-2022-31704将恶意文件写入服务器，从而导致远程代码执行。

### CVE-2022-31710: VMware vRealize Log Insight 反序列化漏洞

CVE: CVE-2022-31710

组件: vRealize Log Insight

漏洞类型: 反序列化

影响: 拒绝服务

简述: 该漏洞存在于vRealize Log Insight中，是一个反序列化漏洞。未经身份验证的攻击者可以远程触发不可信数据的反序列化，这可能导致拒绝服务。

### CVE-2022-31711: VMware vRealize Log Insight信息泄露漏洞

CVE: CVE-2022-31711

组件: vRealize Log Insight

漏洞类型: 信息泄露

影响: 敏感数据泄漏

简述: 该漏洞存在于vRealize Log Insight中，是一个信息泄露漏洞。攻击者可以在未经身份验证的情况下远程收集敏感会话和应用程序信息。

## 0x04  影响版本

| 组件                                                  | 影响版本     | 安全版本      |
| ----------------------------------------------------- | ------------ | ------------- |
| VMware vRealize Log Insight                           | 8.x < 8.10.2 | 8.x >= 8.10.2 |
| VMware Cloud Foundation (VMware vRealize Log Insight) | 3.x          | -             |
| VMware Cloud Foundation (VMware vRealize Log Insight) | 4.x          | -             |

## 0x05  修复建议

### 通用修补建议

根据`影响版本`中的信息，排查并升级到`安全版本`。

#### VMware vRealize Log Insight

下载链接：https://docs.vmware.com/en/vRealize-Log-Insight/8.10.2/rn/vrealize-log-insight-8102-release-notes/index.html

#### VMware Cloud Foundation (VMware vRealize Log Insight)

参考链接：https://kb.vmware.com/s/article/90668

### 临时修补建议

可参考VMware官方给出的修复方案：

https://kb.vmware.com/s/article/90635