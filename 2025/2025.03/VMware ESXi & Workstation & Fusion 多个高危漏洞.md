# VMware ESXi & Workstation & Fusion 多个高危漏洞 (CVE-2025-22224/CVE-2025-22225/CVE-2025-22226)

## 0x01   漏洞简述

VMware 发布安全公告，修复了 VMware ESXi&Workstation&Fusion 多个高危漏洞 (CVE-2025-22224/CVE-2025-22225/CVE-2025-22226)，目前 3 个漏洞均已发现在野利用。

- CVE-2025-22224：VMware ESXi 和 Workstation 中存在 TOCTOU（CheckTime-of-use）越界写入漏洞，具有虚拟机管理权限的攻击者可通过主机上运行的虚拟机 VMX 进程执行任意代码。CVSS 评分 9.3。
- CVE-2025-22225：VMware ESXi 中存在任意写入漏洞，具有 VMX 进程特权的攻击者可通过触发任意内核写入实现沙箱逃逸。CVSS 评分 8.2。
- CVE-2025-22226：HGFS 中存在越界读取漏洞，具有虚拟机管理权限的攻击者可通过 VMX 进程获取内存信息。CVSS 评分 7.1。

VMware 是一家提供虚拟化解决方案的软件公司，它提供了多个虚拟化产品，其中包括 VMware ESXi 虚拟化操作系统、VMware Workstation、VMware vSphere 虚拟化平台，以及各种管理和监控工具等。

**受影响版本：**

- CVE-2025-22224/CVE-2025-22225/CVE-2025-22226

```
VMware ESXi 8.0 U3d < ESXi80U3d-24585383
VMware ESXi 8.0 U2d < ESXi80U2d-24585300
VMware ESXi 7.0 < ESXi70U3s-24585291
VMware Cloud Foundation 5.x < ESXi80U3d-24585383
VMware Cloud Foundation 4.5.x < ESXi70U3s-24585291
VMware Telco Cloud Platform 5.x/4.x/3.x/2.x < KB389385
VMware Telco Cloud Infrastructure 3.x/2.x < KB389385
```

- CVE-2025-22224/CVE-2025-22226

```
VMware Workstation 17.x < 17.6.3
```

- CVE-2025-22226

```
VMware Fusion 13.x < 13.6.3
```

**不受影响版本：**

- CVE-2025-22224/CVE-2025-22225/CVE-2025-22226

```
VMware ESXi 8.0 U3d >= ESXi80U3d-24585383
VMware ESXi 8.0 U2d >= ESXi80U2d-24585300
VMware ESXi 7.0 >= ESXi70U3s-24585291
VMware Cloud Foundation 5.x >= ESXi80U3d-24585383
VMware Cloud Foundation 4.5.x >= ESXi70U3s-24585291
VMware Telco Cloud Platform 5.x/4.x/3.x/2.x >= KB389385
VMware Telco Cloud Infrastructure 3.x/2.x >= KB389385
```

- CVE-2025-22224/CVE-2025-22226

```
VMware Workstation 17.x >= 17.6.3
```

- CVE-2025-22226

```
VMware Fusion 13.x >= 13.6.3
```

## 0x02   风险等级

| 评定方式            | 等级              |
| --------------- | --------------- |
| 威胁等级            | 高危              |
| 影响面             | 广泛              |
| 攻击者价值           | 高               |
| 利用难度            | 低               |
| CVSS 4.0/3.x 评分 | 9.3 / 8.2 / 7.1 |

## 0x03   漏洞详情

### 披露时间

2025-03-04

### 参考链接

- https://support.broadcom.com/web/ecx/support-content-notification/-/external/content/SecurityAdvisories/0/25390
- https://github.com/vmware/vcf-security-and-compliance-guidelines/tree/main/security-advisories/vmsa-2025-0004

## 0x04   修复建议

### 通用修补建议

VMware 已发布关键安全公告 [VMSA-2025-0004](https://support.broadcom.com/web/ecx/support-content-notification/-/external/content/SecurityAdvisories/0/25390) 并提供相应补丁，修复上述漏洞：

|                                   |                    |                |                                                |                                                                                                                                                                                                                                                                                             |              |                                                                                                                                                                                                 |                 |                                                                                                 |
| --------------------------------- | ------------------ | -------------- | ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- | ----------------------------------------------------------------------------------------------- |
| **VMware Product**                | **Version**        | **Running On** | **CVE**                                        | **CVSSv3**                                                                                                                                                                                                                                                                                  | **Severity** | **Fixed Version**                                                                                                                                                                               | **Workarounds** | **Additional Documentation**                                                                    |
| VMware ESXi                       | 8.0                | Any            | CVE-2025-22224, CVE-2025-22225, CVE-2025-22226 | [9.3](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H), [8.2](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H), [7.1](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:N/A:N) | Critical     | [ESXi80U3d-24585383](https://techdocs.broadcom.com/us/en/vmware-cis/vsphere/vsphere/8-0/release-notes/esxi-update-and-patch-release-notes/vsphere-esxi-80u3d-release-notes.html)                | None            | [FAQ](https://brcm.tech/vmsa-2025-0004)                                                         |
| VMware ESXi                       | 8.0                | Any            | CVE-2025-22224, CVE-2025-22225, CVE-2025-22226 | [9.3](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H), [8.2](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H), [7.1](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:N/A:N) | Critical     | [ESXi80U2d-24585300](https://techdocs.broadcom.com/us/en/vmware-cis/vsphere/vsphere/8-0/release-notes/esxi-update-and-patch-release-notes/vsphere-esxi-80u2d-release-notes.html)                | None            | [FAQ](https://brcm.tech/vmsa-2025-0004)                                                         |
| VMware ESXi                       | 7.0                | Any            | CVE-2025-22224, CVE-2025-22225, CVE-2025-22226 | [9.3](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H), [8.2](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H), [7.1](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:N/A:N) | Critical     | [ESXi70U3s-24585291](https://techdocs.broadcom.com/us/en/vmware-cis/vsphere/vsphere/7-0/release-notes/esxi-update-and-patch-release-notes/vsphere-esxi-70u3s-release-notes.html)                | None            | [FAQ](https://brcm.tech/vmsa-2025-0004)                                                         |
| VMware Workstation                | 17.x               | Any            | CVE-2025-22224,  CVE-2025-22226                | [9.3](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H), [7.1](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:N/A:N)                                                                                                | Critical     | 17.6.3                                                                                                                                                                                          | None            | [FAQ](https://brcm.tech/vmsa-2025-0004)                                                         |
| VMware Fusion                     | 13.x               | Any            | CVE-2025-22226                                 | [7.1](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:N/A:N)                                                                                                                                                                                               | Important    | 13.6.3                                                                                                                                                                                          | None            | [FAQ](https://brcm.tech/vmsa-2025-0004)                                                         |
| VMware Cloud Foundation           | 5.x                | Any            | CVE-2025-22224, CVE-2025-22225, CVE-2025-22226 | [9.3](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H), [8.2](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H), [7.1](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:N/A:N) | Critical     | Async patch to [ESXi80U3d-24585383](https://techdocs.broadcom.com/us/en/vmware-cis/vsphere/vsphere/8-0/release-notes/esxi-update-and-patch-release-notes/vsphere-esxi-80u3d-release-notes.html) | None            | Async Patching Guide: [KB88287](https://knowledge.broadcom.com/external/article?legacyId=88287) |
| VMware Cloud Foundation           | 4.5.x              | Any            | CVE-2025-22224, CVE-2025-22225, CVE-2025-22226 | [9.3](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H), [8.2](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H), [7.1](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:N/A:N) | Critical     | Async patch to [ESXi70U3s-24585291](https://techdocs.broadcom.com/us/en/vmware-cis/vsphere/vsphere/7-0/release-notes/esxi-update-and-patch-release-notes/vsphere-esxi-70u3s-release-notes.html) | None            | Async Patching Guide: [KB88287](https://knowledge.broadcom.com/external/article?legacyId=88287) |
| VMware Telco Cloud Platform       | 5.x, 4.x, 3.x, 2.x | Any            | CVE-2025-22224, CVE-2025-22225, CVE-2025-22226 | [9.3](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H), [8.2](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H), [7.1](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:N/A:N) | Critical     | [KB389385](https://knowledge.broadcom.com/external/article/389385)                                                                                                                              | None            | [FAQ](https://brcm.tech/vmsa-2025-0004)                                                         |
| VMware Telco Cloud Infrastructure | 3.x, 2.x           | Any            | CVE-2025-22224, CVE-2025-22225, CVE-2025-22226 | [9.3](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H), [8.2](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H), [7.1](https://www.first.org/cvss/calculator/3.1#CVSS:3.1/AV:L/AC:L/PR:N/UI:N/S:C/C:H/I:N/A:N) | Critical     | [KB389385](https://knowledge.broadcom.com/external/article/389385)                                                                                                                              | None            | [FAQ](https://brcm.tech/vmsa-2025-0004)                                                         |
