# 知识点 ↔ 原文映射

来源总站：[Delikely's Blog](https://delikely.eu.org/)

## 基础与体系

| 知识点 | 建议阅读 |
|--------|----------|
| 术语 / 黑话 | [术语(黑话)集](https://delikely.eu.org/2026/07/10/autosec-glossary/) |
| 组织机构 | [常见组织机构](https://delikely.eu.org/2024/07/05/autosec-corp-panorama/) |
| 模块化平台 / EE 架构 | [汽车模块化平台](https://delikely.eu.org/2021/07/25/Automotive-Modular-Platform/)、[大众集团 EE 架构](https://delikely.eu.org/2021/07/30/VW-Electronic/) |
| 质量管理与开发流程 | [质量管理&整车开发流程](https://delikely.eu.org/2025/05/05/Quality-Management-and-Vehicle-Development-Process/) |
| 风险评级 | [GB-T45496 漏洞风险等级计算器](https://delikely.eu.org/2025/06/17/GB-T45496-Calculator/) |
| 接插件 / 端子 | [ECU 接插件](https://delikely.eu.org/2024/06/07/ecu-connectors/)、[插线端子看网络结构](https://delikely.eu.org/2021/11/18/Vehicle-Cable-Connection-Terminal/) |
| 数据库文件 | [数据库文件](https://delikely.eu.org/2024/11/15/automotive-DB-file-set/) |

## 漏洞挖掘 / 渗透（含灰黑盒）

| 知识点 | 建议阅读 |
|--------|----------|
| 整车渗透 / 黑白灰盒定义 | [整车渗透测试实践](https://delikely.eu.org/2023/10/10/pentest-workflow-for-automotive/) |
| 灰黑盒逻辑整合（本库） | [black-gray-box.md](black-gray-box.md) |
| TBOX / OCU | [大众 J949 OCU/TBOX](https://delikely.eu.org/2021/09/29/VW-OCU/)、[TBOX 主要功能](https://delikely.eu.org/2021/08/15/TBOX-Main-Function/) |
| 车机 USB 提权 | [U盘目录穿越获取车机 SHELL](https://delikely.eu.org/2021/06/04/U%E7%9B%98%E7%9B%AE%E5%BD%95%E7%A9%BF%E8%B6%8A%E8%8E%B7%E5%8F%96%E8%BD%A6%E6%9C%BASHELL/) |
| ADB 半授权 | [Tesla TCU ADB 认证绕过复现](https://delikely.eu.org/2025/12/27/Tesla-TCU-ADB-Bypass-Reproduction/) |
| Tesla 固件 | [从磁盘映像提取文件系统](https://delikely.eu.org/2021/03/10/Tesla%E8%BD%A6%E6%9C%BA%E5%9B%BA%E4%BB%B6%E5%88%86%E6%9E%90%E7%AC%AC%E4%B8%80%E6%AD%A5%EF%BC%9A%E4%BB%8E%E7%A3%81%E7%9B%98%E6%98%A0%E5%83%8F%E4%B8%AD%E6%8F%90%E5%8F%96%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F/) |
| 充电桩 | [充电桩漏洞挖掘实践](https://delikely.eu.org/2022/04/29/chargebox-vuln-hunter-garo-and-bender/) |
| 跨境传输 | [跨境传输检测](https://delikely.eu.org/2023/05/14/cross-border-check/) |
| 车机 Python 测试环境 | [Android 车机运行 Python](https://delikely.eu.org/2023/11/16/pydroid/) |

## 固件与硬件

| 知识点 | 建议阅读 |
|--------|----------|
| 免拆提取固件 | [免拆芯片提取固件](https://delikely.eu.org/2021/01/11/%E5%85%8D%E6%8B%86%E8%8A%AF%E7%89%87%E6%8F%90%E5%8F%96%E5%9B%BA%E4%BB%B6/)、[汽车中的应用](https://delikely.eu.org/2021/01/30/%E5%85%8D%E6%8B%86%E8%8A%AF%E7%89%87%E6%8F%90%E5%8F%96%E5%9B%BA%E4%BB%B6%E5%9C%A8%E6%B1%BD%E8%BD%A6%E4%B8%AD%E7%9A%84%E5%BA%94%E7%94%A8/) |
| MCU 分析 | [STM8 固件提取与分析](https://delikely.eu.org/2021/07/17/STM8%E5%9B%BA%E4%BB%B6%E6%8F%90%E5%8F%96%E4%B8%8E%E5%88%86%E6%9E%90/) |
| QNX | [QNX Command Cheatsheet](https://delikely.eu.org/2022/02/28/QNX-Command-Cheatsheet/) |

## 诊断 / 刷写 / OTA / 协议栈

| 知识点 | 建议阅读 |
|--------|----------|
| 协议栈深入分析（本库） | [protocol-stack.md](protocol-stack.md) |
| 网络域 / 端子拓扑 | [插线端子看网络结构](https://delikely.eu.org/2021/11/18/Vehicle-Cable-Connection-Terminal/) |
| 协议字典（DBC/ODX/…） | [数据库文件](https://delikely.eu.org/2024/11/15/automotive-DB-file-set/) |
| UDS 刷写安全 | [UDS 刷写](https://delikely.eu.org/2023/05/01/UDS-flash/) |
| OBD | [OBD-II 标准阅读](https://delikely.eu.org/2021/04/29/2021-WIDC%E4%BF%A1%E6%81%AF%E5%AE%89%E5%85%A8%E6%8C%91%E6%88%98%E8%B5%9B%E9%A2%84%E8%B5%9B%E5%9B%9E%E9%A1%BE%E4%B8%8EOBD-II%E6%A0%87%E5%87%86%E9%98%85%E8%AF%BB/) |
| 车机侧协议脚本环境 | [Android 车机运行 Python](https://delikely.eu.org/2023/11/16/pydroid/) |

## 防御与工程化

结合原文中的「安全启动 / 安全访问 / 加密传输 / 调试接口管控」等建议，见本库 `index.html` 防御专章与 `checklist.md`。
