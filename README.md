# CVE

**❗【免责声明】本项目所涉及的技术、思路和工具仅供学习，任何人不得将其用于非法用途和盈利，不得将其用于非授权渗透测试，否则后果自行承担，与本项目无关。 使用本项目前请先阅读 [法律法规](https://github.com/Threekiii/Awesome-Laws)。**

_Disclaimer: The technologies, concepts, and tools provided in this Git repository are intended for educational and research purposes only. Any use for illegal activities, unauthorized penetration testing, or commercial purposes is strictly prohibited. Please read the [Awesome-Laws](https://github.com/Threekiii/Awesome-Laws) before using this repository._

📖 一个 CVE 漏洞预警知识库，无 exp/poc，部分包含修复方案。_A knowledge base of CVE security vulnerability, no PoCs/exploits._

## 0x01 项目导航
  - 2025.06
     *  CVE-2025-1750：llama_index DuckDBVectorStore SQL 注入.md
     *  CVE-2024-29198：GeoServer TestWFSpost SSRF 漏洞.md
     *  CVE-2025-27818：Apache Kafka Client LdapLoginModule 配置代码执行漏洞.md
     *  CVE-2025-6018：SUSE 15 PAM 本地提权漏洞.md
     *  CVE-2025-6019：libblockdev 权限提升漏洞.md
     *  CVE-2025-30220：Geoserver GeoTools XXE 漏洞.md
     *  CVE-2025-49596：MCP Inspector 未授权访问致代码执行漏洞.md
     *  CVE-2025-49002：Dataease H2 数据库远程代码执行漏洞.md
     *  CVE-2025-49113：Roundcube Webmail upload.php 反序列化代码执行漏洞.md
     *  CVE-2025-49001：Dataease JWT 认证绕过漏洞.md

  - 2025.05
     *  CVE-2025-4428：Ivanti Endpoint Manager Mobile 模版注入远程代码执行漏洞.md
     *  CVE-2024-24780：Apache IoTDB UDF 远程代码执行漏洞.md
     *  CVE-2025-47277：vLLM PyNcclPipe pickle反序列化漏洞.md
     *  CVE-2025-48827：vBulletin replaceAdTemplat 远程代码执行漏洞.md

  - 2025.04
     *  CVE-2025-34028：Commvault SSRF 致代码执行漏洞.md
     *  CVE-2025-3248：Langflow code 代码执行漏洞.md
     *  CVE-2025-31486：Vite 开发服务器任意文件读取漏洞.md
     *  CVE-2025-31125：Vite 开发服务器任意文件读取漏洞.md
     *  CVE-2025-32432：Craft CMS generate-transform 反序列化代码执行漏洞.md
     *  CVE-2025-31324：SAP Netweaver metadatauploader 代码执行漏洞.md
     *  browser-use WebUI pickle 反序列化漏洞.md

  - 2025.03
     *  VMware ESXi & Workstation & Fusion 多个高危漏洞.md
     *  CVE-2025-2825：Crushftp 认证绕过漏洞.md
     *  CVE-2025-29927：Next.js 中间件权限绕过漏洞.md
     *  CVE-2025-30208：Vite开发服务器任意文件读取漏洞.md
     *  CVE-2025-24514：Kubernetes ingress-nginx controller auth-url 配置注入漏洞.md
     *  CVE-2025-1974：Kubernetes Ingress-nginx admission 远程代码执行漏洞.md
     *  CVE-2025-1098：Kubernetes Ingress-nginx mirror-target和mirror-host 配置注入漏洞.md
     *  CVE-2025-24513：Kubernetes ingress-nginx auth secret file 目录遍历漏洞.md
     *  CVE-2025-24813：Apache Tomcat Partial PUT远程代码执行漏洞.md
     *  CVE-2025-1097：Kubernetes Ingress-nginx auth-tls-match-cn 配置注入漏洞.md

  - 2025.02
     *  CVE-2025-0108：Palo Alto Networks PAN-OS Management 管理端权限绕过漏洞.md
     *  CVE-2024-48248：NAKIVO Backup & Replication 任意文件读取漏洞.md

  - 2025.01
     *  CVE-2025-0282：Ivanti Connect Secure 栈溢出漏洞.md
     *  CVE-2025-24367：Cacti 任意文件创建致远程代码执行漏洞.md
     *  CVE-2025-22604：Cacti 多行SNMP响应验证致代码执行漏洞.md

  - 2024.12
     *  CVE-2024-50379：Apache Tomcat 条件竞争文件上传漏洞.md
     *  CVE-2024-43441：Apache HugeGraph-Server JWT 权限绕过漏洞.md
     *  CVE-2024-53376：Cyber​​Panel操作系统命令注入漏洞.md
     *  CVE-2024-56145：Craft CMS register_argc_argv 模板注入代码执行漏洞.md
     *  CVE-2024-56337：Apache Tomcat 条件竞争文件上传漏洞.md
     *  CVE-2024-53677：Apache Struts FileUploadInterceptor 目录遍历与文件上传漏洞.md

  - 2024.11
     *  CVE-2024-47208：Apache OFBiz Groovy表达式注入漏洞.md
     *  CVE-2024-42327：Zabbix user.get API SQL 注入漏洞.md
     *  CVE-2024-50340：Symfony runtime 变量可控漏洞.md
     *  CVE-2024-51504：Apache ZooKeeper Admin Server IPAuthenticationProvider 认证绕过漏洞.md
     *  CVE-2024-0012：Palo Alto Networks PAN-OS Management Web Interface 权限绕过漏洞.md

  - 2024.10
     *  CVE-2024-38819：Spring Framework 特定条件下目录遍历漏洞.md
     *  CVE-2024-45216：Apache Solr 认证绕过漏洞.md
     *  CVE-2024-51567：CyberPanel upgrademysqlstatus 远程命令执行漏洞.md
     *  CVE-2024-47575：Fortinet FortiManager 身份认证绕过漏洞.md
     *  CVE-2024-31449：Redis Lua Script 溢出漏洞.md

  - 2024.09
     *  CVE-2024-45507：Apache OFBiz SSRF致代码执行漏洞.md
     *  CVE-2024-29847：Ivanti Endpoint Manager Agent Portal 存在反序列化漏洞.md
     *  CVE-2024-9014：pgAdmin4 OAuth2 client ID与secret敏感信息泄漏漏洞.md
     *  CVE-2024-37288：Kibana 8.15.1 Amazon Bedrock YAML 反序列化漏洞.md
     *  CVE-2024-45409：Gitlab Ruby-SAML 身份认证绕过漏洞.md
     *  CVE-2024-45195：Apache OFBiz 远程代码执行漏洞.md
     *  CVE-2024-37285：Kibana YAML 反序列化代码执行漏洞.md
     *  CVE-2024-38816：Spring Framework 特定条件下目录遍历漏洞.md

  - 2024.08
     *  Nacos Jraft 文件读写漏洞.md
     *  CVE-2024-43044：Jenkins agent connections 文件读取漏洞.md
     *  CVE-2024-37287：Kibana 原型链代码执行漏洞.md
     *  CVE-2024-38856：Apache OFBiz 代码执行漏洞.md
     *  CVE-2024-21689：Atlassian Bamboo 远程代码执行漏洞.md

  - 2024.07
     *  CVE-2024-36991：Splunk Enterprise Windows平台 messaging 目录遍历漏洞.md
     *  CVE-2024-6387：OpenSSH Server 远程代码执行漏洞.md
     *  CVE-2024-36401：GeoServer property 表达式注入代码执行漏洞.md
     *  CVE-2024-23321：Apache RocketMQ 敏感信息泄露漏洞.md
     *  CVE-2024-6730：SparkShop存在任意文件上传漏洞.md
     *  CVE-2024-3807：Windows 远程桌面授权服务 远程代码执行漏洞.md
     *  CVE-2024-37084：Spring Cloud Data Flow 远程代码执行漏洞.md

  - 2024.06
     *  CVE-2024-4577：PHP CGI Windows平台远程代码执行漏洞.md
     *  CVE-2024-37032：Ollama 目录遍历致代码执行漏洞.md
     *  CVE-2024-32030：UI for Apache Kafka 后台 jmx jndi 代码执行漏洞.md
     *  CVE-2024-36522：Apache Wicket XSLT 代码执行漏洞.md
     *  CVE-2024-36104：Apache OFBiz 目录遍历致代码执行漏洞.md

  - 2024.05
     *  CVE-2024-23692：Rejetto HFS 2.x 远程代码执行漏洞.md
     *  CVE-2024-32113：Apache OFBiz 目录遍历致代码执行漏洞.md
     *  CVE-2024-22120：Zabbix Server Audit Log SQL 注入漏洞.md
     *  CVE-2024-26026：F5 BIG-IP Next Central Manager SQL注入漏洞.md
     *  CVE-2024-24919：CheckPoint Gateway 文件读取漏洞.md
     *  CVE-2024-21683：Atlassian Confluence 登陆后代码执行漏洞.md
     *  CVE-2024-4956：Nexus Repository 3 目录遍历与文件读取漏洞.md
     *  CVE-2024-32640：Mura CMS processAsyncObject SQL注入漏洞.md

  - 2024.04
     *  CVE-2024-32113：Apache OFBiz 目录遍历致代码执行漏洞.md
     *  CVE-2024-26026：F5 BIG-IP Next Central Manager SQL注入漏洞.md
     *  2024-04 补丁日：Oracle多个产品漏洞安全风险通告.md
     *  CVE-2024-32114：Apache ActiveMQ Jolokia REST API 未授权访问漏洞.md

  - 2024.03
     *  CVE-2024-27198：JetBrains TeamCity 身份验证绕过漏洞通告.md
     *  CVE-2024-25065：Apache OFBiz目录遍历漏洞通告.md

  - 2024.02
     *  CVE-2024-25600：WordPress Bricks Builder远程命令执行漏洞通告.md
     *  CVE-2024-21626：runc容器逃逸漏洞通告.md
     *  CVE-2024-21413：Microsoft Outlook 远程代码执行漏洞通告.md
     *  2024-02 补丁日：微软多个漏洞安全更新通告.md

  - 2024.01
     *  CVE-2024-0204：GoAnywhere MFT 身份认证绕过漏洞通告.md
     *  CVE-2024-0519：Google Chrome V8越界访问漏洞通告.md
     *  2024-01 补丁日：微软多个漏洞安全更新通告.md
     *  CVE-2023-22527：Atlassian Confluence 远程代码执行漏洞通告.md

  - 2023.12
     *  CVE-2023-51467：Apache OFBiz 未授权远程代码执行漏洞通告.md
     *  CVE-2023-50164：Apache Struts 代码执行漏洞通告.md
     *  CVE-2023-49070：Apache OFBiz 未授权远程代码执行漏洞通告.md
     *  CVE-2022-41678：Apache ActiveMQ Jolokia 远程代码执行漏洞通告.md
     *  2023-12 补丁日：微软多个漏洞安全更新通告.md

  - 2023.11
     *  CVE-2023-4357：Google Chrome 信息泄露漏洞通告.md
     *  CVE-2023-6345：Google Chrome skia整数溢出漏洞通告.md
     *  CVE-2023-22518：Atlassian Confluence身份认证绕过漏洞通告.md
     *  2023-11 补丁日：微软多个漏洞安全更新通告.md

  - 2023.10
     *  CVE-2023-36802：Microsoft 流式处理代理权限提升漏洞通告.md
     *  CVE-2023-42824：Apple iOS iPadOS 本地权限提升漏洞通告.md
     *  CVE-2023-34051：VMware Aria Operations for Logs 远程代码执行漏洞通告.md
     *  2023-10 补丁日 Oracle多个产品漏洞安全风险通告.md
     *  Apache ActiveMQ远程代码执行漏洞通告.md
     *  CVE-2023-20198：Cisco IOS XE Web UI 权限提升漏洞通告.md
     *  CVE-2023-4966：Citrix NetScaler信息泄露漏洞通告.md
     *  2023-10 补丁日 微软多个漏洞安全更新通告.md
     *  CVE-2023-46747：F5 BIG-IP 远程代码执行漏洞通告.md

  - 2023.09
     *  CVE-2023-5217：Google Chrome libvpx堆缓冲区溢出漏洞通告.md
     *  CVE-2023-42820：JumpServer密码重置漏洞.md
     *  致远OA前台任意用户密码重置漏洞通告.md
     *  CVE-2023-39361：Cacti 前台SQL注入漏洞通告.md
     *  CVE-2023-38146：Windows Themes远程代码执行漏洞通告.md
     *  CVE-2023-4863：Google Chrome webp堆缓冲区溢出漏洞通告.md
     *  CVE-2023-4998：GitLab 身份认证绕过漏洞通告.md
     *  CVE-2023-42442：JumpServer未授权访问漏洞通告.md
     *  2023-09 补丁日：微软多个漏洞安全更新通告.md
     *  CVE-2023-35359：Windows 内核权限提升漏洞通告.md
     *  CVE-2023-26369：Adobe Acrobat Reader 代码执行漏洞通告.md

  - 2023.08
     *  Smartbi身份认证绕过漏洞通告-20230824.md
     *  QNAP 多个高危漏洞通告.md
     *  VMware Aria Operations for Networks 身份认证绕过漏洞通告.md
     *  CVE-2023-38831：RARLAB WinRAR代码执行漏洞通告.md
     *  CVE-2023-36874：Windows 错误报告服务权限提升漏洞通告.md
     *  Smartbi身份认证绕过漏洞通告-20230803.md

  - 2023.07
     *  CVE-2023-38646：Metabase远程命令执行漏洞通告.md
     *  CVE-2023-37582：Apache RocketMQ 远程代码执行漏洞通告.md
     *  泛微E-Cology SQL注入漏洞安全通告.md
     *  CVE-2023-31248：Linux Kernel 本地权限提升漏洞通告.md
     *  CVE-2023-34478：Apache Shiro 身份认证绕过漏洞通告.md
     *  CVE-2023-3519：Citrix ADC Gateway 远程代码执行漏洞通告.md
     *  CVE-2023-38408：OpenSSH ssh-agent 远程代码执行漏洞通告.md
     *  Smartbi 多个高危漏洞通告.md
     *  2023-07 补丁日 微软多个漏洞安全更新通告.md
     *  Atlassian 多个代码执行漏洞通告.md

  - 2023.06
     *  CVE-2023-3079：Google V8类型混淆漏洞通告.md
     *  CVE-2023-20887：VMware Aria Operations for Networks命令注入漏洞通告.md
     *  CVE-2023-3128：Grafana 身份认证绕过漏洞通告.md
     *  CVE-2023-27997：Fortinet FortiOS SSL-VPN 远程代码执行漏洞通告.md
     *  2023-06 补丁日：微软多个漏洞安全更新通告.md
     *  CVE-2023-1829：Linux Kernel权限提升漏洞通告.md
     *  CVE-2023-33299：FortiNAC 反序列化漏洞通告.md
     *  Nacos 集群 Raft 反序列化漏洞通告.md

  - 2023.05
     *  Apple WebKit 多个漏洞通告.md
     *  CVE-2023-29324：Windows MSHTML Platform安全功能绕过漏洞通告.md
     *  CVE-2023-2478：GitLab 代码执行漏洞通告.md
     *  泛微多个漏洞通告.md
     *  CVE-2023-0386：Linux Kernel 权限提升漏洞通告.md
     *  CVE-2023-33246：Apache RocketMQ 远程代码执行漏洞通告.md
     *  CVE-2023-32233：Linux Kernel 权限提升漏洞通告.md
     *  CVE-2023-2825：GitLab 目录遍历漏洞通告.md
     *  2023-05 补丁日 微软多个漏洞安全更新通告.md

  - 2023.04
     *  CVE-2023-29017：vm2沙箱逃逸漏洞通告.md
     *  CVE-2023-27524：Apache Superset身份认证绕过漏洞通告.md
     *  2023-04 补丁日：Oracle多个产品漏洞安全风险通告.md
     *  瑞友天翼应用虚拟化系统远程代码执行漏洞通告.md
     *  CVE-2023-2136：Google Chrome Skia整型溢出漏洞通告.md
     *  2023-04 补丁日：微软多个漏洞安全更新通告.md
     *  CVE-2023-20869 20870：VMware Workstation&Fusion 漏洞通告.md
     *  CVE-2023-20864 VMware Aria Operations for Logs远程代码执行漏洞.md
     *  CVE-2023-2033：Google Chrome V8类型混淆漏洞通告.md

  - 2023.03
     *  CVE-2023-22809：Sudo权限提升漏洞通告.md
     *  CVE-2023-28432：MinIO信息泄露漏洞通告.md
     *  CVE-2023-20860：Spring Framework身份验证绕过漏洞通告.md
     *  CVE-2023-23397：Microsoft Outlook权限提升漏洞通告.md
     *  CVE-2023-29059：3CXDesktop App 代码执行漏洞通告.md
     *  CVE-2023-27898 27905：Jenkins跨站脚本漏洞通告.md
     *  CVE-2023-21716：Microsoft Word 远程代码执行漏洞通告.md
     *  Smartbi远程命令执行漏洞通告.md
     *  2023-03 补丁日 微软多个漏洞安全更新通告.md
     *  CVE-2023-0050：GitLab跨站脚本漏洞通告.md
     *  CVE-2023-25610：FortiOS & FortiProxy 远程代码执行漏洞通告.md
     *  CVE-2023-21768：Windows Ancillary Function 本地权限提升漏洞通告.md
     *  CVE-2023-23638：Apache Dubbo反序列化漏洞通告.md

  - 2023.02
     *  CVE-2023-24998：Apache Commons FileUpload拒绝服务漏洞通告.md
     *  CVE-2023-23529：Apple WebKit任意代码执行漏洞通告.md
     *  CVE-2023-22482 22736：Argo CD 身份验证绕过漏洞通告.md
     *  CVE-2021-42756 CVE-2022-39952：Fortinet 多个漏洞通告.md
     *  CVE-2023-23477：IBM WebSphere Application Server远程代码执行漏洞通告.md
     *  CVE-2023-22374：F5 BIG-IP任意代码执行漏洞通告.md
     *  CVE-2023-23752：Joomla未授权访问漏洞通告.md
     *  2023-02 补丁日 微软多个漏洞安全更新通告.md
     *  泛微e-cology9 SQL注入漏洞通告.md
     *  CVE-2023-22501：Jira Service Management ServerData Center 身份验证漏洞通告.md
     *  CVE-2023-25725：HAProxy请求走私漏洞通告.md
     *  CVE-2023-20858：VMware Carbon Black App Control 远程代码执行漏洞通告.md
     *  CVE-2023-25194：Apache Kafka Connect 远程代码执行漏洞通告.md
     *  CVE-2023-21608：Adobe Acrobat Reader 任意代码执行漏洞通告.md

  - 2023.01
     *  CVE-2022-43396 44621：Apache Kylin命令注入漏洞通告.md
     *  CVE-2022-39947 35845：Fortinet 命令注入漏洞通告.md
     *  CVE-2022-43931：Synology VPN Plus Server越界写入漏洞通告.md
     *  CVE-2023-23560：Lexmark打印机服务器端请求伪造漏洞通告.md
     *  CVE-2022-45935：Apache James Server信息泄露漏洞通告.md
     *  CVE-2022-47966：Zoho ManageEngine OnPremise多款产品远程代码执行漏洞通告.md
     *  CVE-2022-27596：QNAP QTSQuTS hero SQL注入漏洞通告.md
     *  CVE-2023-22602：Apache Shiro身份认证绕过漏洞通告.md
     *  CVE-2023-21839：WebLogic 远程代码执行漏洞通告.md
     *  VMware vRealize Log Insight多个高危漏洞通告.md
     *  CVE-2023-21752：Windows Backup Service权限提升漏洞通告.md

  - 2022.12
     *  CVE-2022-41080 41082：Microsoft Exchange Server OWASSRF漏洞通告.md
     *  CVE-2022-41966：XStream 拒绝服务漏洞通告.md
     *  CVE-2022-42475：Fortinet SSL VPN远程代码执行漏洞.md
     *  CVE-2022-46169：Cacti 命令注入漏洞.md
     *  CVE-2022-3328：Snapd 本地权限提升漏洞通告.md
     *  CVE-2022-45347：Apache ShardingSphere身份认证绕过漏洞通告.md
     *  CVE-2022-4262：Google Chrome V8类型混淆漏洞通告.md
## 0x02 声明

本项目收集 CVE 漏洞预警均源于互联网：

- [360 CERT](https://cert.360.cn/)
- [阿里云漏洞库](https://avd.aliyun.com/)
- [长亭安全应急响应中心](https://stack.chaitin.com/vuldb/index)
