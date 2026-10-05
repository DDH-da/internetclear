# internetclear
本项目是一个面向终端用户的 网络流量净化系统 ，旨在解决运营商 DNS 劫持、HTTP 中间人篡改及 ISP 恶意代码植入三大网络安全问题。系统采用前后端分离架构：后端基于纯 Python 实现（零第三方依赖），内置 DNS 代理、HTTP 代理与 Web 控制界面三大服务，构建了从域名解析拦截、恶意 URL 过滤、HTTPS 强制升级到浏览器端脚本注入防护的 六层纵深防御体系 ；前端采用 React + TypeScript + Three.js 技术栈，搭配 Tailwind CSS 与 Zustand 状态管理，打造了具有粒子背景、3D 机械核心可视化与实时威胁仪表盘的 赛博朋克风格交互界面 。
