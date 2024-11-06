# Atlassian 多个代码执行漏洞通告

报告编号：CERT-R-2023-300

更新日期：2023-07-24

## 0x01  漏洞简述

2023年07月24日，360CERT监测发现`Atlassian`发布了`Confluence Data Center,Confluence Data Center,Bamboo Data Center`的风险通告，漏洞编号为`CVE-2023-22505,CVE-2023-22508,CVE-2023-22506`，事件等级：`高危`，事件评分：`8.5`。

Atlassian Confluence Data Center & Server 是 Atlassian 公司提供的一款企业级团队协作和知识管理软件。它旨在帮助团队协同工作、共享知识、记录文档和协作编辑等。

## 0x02  风险等级

该漏洞的评定结果如下

| 评定方式    | 等级 |
| ----------- | ---- |
| 威胁等级    | 高危 |
| 影响面      | 广泛 |
| 攻击者价值  | 高   |
| 利用难度    | 低   |
| 360CERT评分 | 8.5  |

## 0x03  漏洞详情

### CVE-2023-22505 远程代码执行漏洞

组件: Atlassian:Confluence Data Center, Atlassian:Confluence Server

漏洞类型: 程序逻辑错误

实际影响: 远程代码执行

主要影响: 服务器接管

简述: 该漏洞存在于Confluence 数据中心和服务器中，是一个远程代码执行漏洞。经过身份验证的攻击者可利用该漏洞，在无用户交互的情况下，在Confluence 数据中心和服务器中执行任意代码，可能造成服务器接管。

### CVE-2023-22508 远程代码执行漏洞

组件: Atlassian:Confluence Data Center, Atlassian:Confluence server

漏洞类型: 程序逻辑错误

实际影响: 远程代码执行

主要影响: 服务器接管

简述: 该漏洞存在于Confluence Data Center & Server 7.4.0 中，是一个远程代码执行漏洞。经过身份验证的攻击者可利用该漏洞，在无用户交互的情况下，在Confluence Data Center & Server上执行任意代码，最终可能接管服务器。

### CVE-2023-22506 远程代码执行漏洞

组件: Atlassian:Bamboo Data Center, Atlassian:Bamboo Server

漏洞类型: 程序逻辑错误

实际影响: 远程代码执行

主要影响: 服务器接管

简述: 该漏洞存在于Bamboo Data Center 8.0.0 版本中，是一个远程代码执行漏洞。经过身份验证的攻击者可利用该漏洞，修改系统调用所采取的操作并执行任意代码，可能导致服务器接管。

## 0x04  影响版本

### CVE-2023-22505

| 组件                             | 影响版本 | 安全版本                  |
| -------------------------------- | -------- | ------------------------- |
| Atlassian:Confluence Data Center | >= 8.0.0 | < 8.0.0,>= 8.3.2,>= 8.4.0 |
| Atlassian:Confluence Server      | >= 8.0.0 | < 8.0.0,>= 8.3.2,>= 8.4.0 |

### CVE-2023-22508

| 组件                             | 影响版本         | 安全版本         |
| -------------------------------- | ---------------- | ---------------- |
| Atlassian:Confluence Data Center | <7.19.8,>= 7.4.0 | 7.19.8 ,>= 8.2.0 |
| Atlassian:Confluence server      | <7.19.8,>= 7.4.0 | 7.19.8,>= 8.2.0  |

### CVE-2023-22506

| 组件                         | 影响版本 | 安全版本                  |
| ---------------------------- | -------- | ------------------------- |
| Atlassian:Bamboo Data Center | >= 8.0.0 | < 8.0.0,>= 9.2.3,>= 9.3.1 |
| Atlassian:Bamboo Server      | >= 8.0.0 | < 8.0.0,>= 9.2.3,>= 9.3.1 |

## 0x05  修复建议

### 通用修补建议

根据`影响版本`中的信息，排查并升级到`安全版本`，或直接访问参考链接获取官方更新指南。