🛡 Web安全学习作品集（DVWA实验记录）
👨‍💻 关于我

信息安全专业学生，主要方向为 Web安全测试与漏洞分析，具备基础渗透测试实践能力。

🎯 项目简介

本仓库基于 DVWA（Damn Vulnerable Web Application）靶场，记录常见Web安全漏洞的学习与实践过程，包括：

SQL注入（SQL Injection）
跨站脚本攻击（XSS：反射型 / 存储型）
Burp Suite抓包与请求分析
HTTP协议与请求结构理解
🔬 实验内容
1️⃣ SQL注入实验
手动构造注入Payload
观察数据库响应变化
验证数据是否可被非法获取
理解SQL语句被篡改的原理
2️⃣ XSS跨站脚本攻击
反射型 XSS
在URL参数中注入脚本
页面直接执行恶意JavaScript代码
验证输入未过滤问题

示例：

<script>alert(1)</script>
存储型 XSS
在留言板提交恶意脚本
数据被存储在服务器端
其他用户访问时自动触发执行
3️⃣ Burp Suite抓包分析
拦截HTTP请求
修改请求参数
重放攻击请求
分析漏洞触发过程
🧰 技术栈
DVWA靶场环境
Burp Suite
Chrome开发者工具
HTTP协议基础
Kali Linux（实验环境）
📸 实验记录（可选加分）

建议在 /assets 文件夹添加截图，例如：

XSS弹窗截图
SQL注入返回结果
Burp抓包请求界面
🧠 技能收获
Web漏洞基本原理理解
HTTP请求结构分析能力
基础渗透测试流程
安全测试思维建立
📌 求职方向
Web安全测试工程师
渗透测试助理
安全测试 / QA安全方向
安全运营（SOC基础岗）
👤 作者

信息安全专业学生
