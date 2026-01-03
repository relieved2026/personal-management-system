<p align="center">
<img src="github/logo.svg" width="100px"/>
</p>

# 个人管理系统 (Personal Management System)

### 后端

这是管理个人数据的核心后端程序。 **注意：这仅包含后端代码！**

### 文档 / 演示

- **前端代码**：[点击此处获取](https://github.com/Volmarg/personal-management-system-front)
- **官方文档**：[点击此处查看](https://volmarg.github.io/personal-management-system-docs/)
- **演示地址**：[点击此处跳转](https://personal-management-system.pl/)
  - **登录账号**：`admin@admin.admin`
  - **密码/锁定密码**：`admin`

## 项目描述

要理解这个 Web 应用程序，可以将其想象为一个 CMS（如 WordPress）或 CRM（如 SugarCRM）；该系统的逻辑与这两者非常相似。虽然我的 PMS 提供的功能可能比上述系统少，但它完全满足我的个人需求。此外，编写扩展插件并不难（取决于所需的逻辑），任何具备开发知识的人都可以根据个人需求编写自己的扩展。

## 开发初衷与目的

1. **定制化**：我决定创建自己的系统，因为折腾大量的 WordPress 插件或在现有的 CRM 上进行二次开发所花费的时间，几乎够我写一个全新的系统了。通过从核心层面了解其逻辑，我能更轻松地编写扩展并添加任何我需要的模块。
2. **数据统一与隐私**：目前市面上没有完全符合我需求的系统。我不想把基于 Docker 的云系统与 CMS 强行整合。此外，我厌倦了将极其私人的数据分散存储（有的在 OneDrive，有的在 Google Cloud，有的在随手记）。
3. **最终目标**：最终目标是让该应用在我的家庭网络中的树莓派（Raspberry Pi）或终端上 24/7 全天候运行，且**无需连接互联网**。

<h3>Preview</h3>
<hr>	

<img src="github/dashboard.png">
<img src="github/contacts.png">
<img src="github/calendar.png">

## 可用选项与模块

- 🎯 **待办事项/目标 (Todo/Goals)**：追踪个人目标。可以使用清单记录进度，或使用支付子模块监控为某项支出筹集的资金。
- 📖 **笔记 (Notes)**：为分类添加个人笔记。存放电话摘要、各处收集的信息或稍后阅读的链接。
- 📞 **联系人 (Contacts)**：整理备份电话和邮箱，防止丢失。
- 🔑 **密码管理 (Passwords)**：数据库中加密存储密码，前端提供一键解密复制按钮。
- 🏆 **成就 (Achievements)**：记录你完成的酷事。
- 📅 **日程表 (Schedules)**：追踪重复性事务（如汽车换油、缴费、预约等），会在仪表盘和通知铃铛中提醒。
- 🔁 **事务追踪 (Issues)**：追踪进行中或待处理的案例，支持记录联系进展，方便日后回顾。
- 🌴 **旅行 (Travels)**：记录旅行想法，支持添加 Google 地图链接和图片。
- 💸 **账单支付 (Payments)**：记录食物、旅行、居家购物等开支并自动计算月度总结。包含“产品价格”子模块（对比不同地区物价）和“欠款管理”。
- 🛒 **购物清单 (Shopping)**：记录未来想买的东西。
- 💻 **工作 (Job)**：
  - *加班子模块*：记录加班时长，可分配给特定目标（如：为了旅游攒够 24 小时假期）。
  - *年假子模块*：追踪年度剩余假期。
- 📷 **图片 (Images)**：以瀑布流画廊形式组织照片/扫描件，支持灯箱预览、重命名和下载。
- 📁 **文件 (Files)**：以表格形式显示上传的文件，支持按扩展名显示图标，支持重命名、下载和删除。
- 🎬 **视频 (Video)**：存储并播放常见的 Web 视频格式。
- 📑 **报告 (Reports)**：基于数据库现有数据生成的只读报告。

------

## 安装与技术栈

- **安装步骤**：请参考 [官方文档](https://volmarg.github.io/personal-management-system-docs/)。
- **技术框架**：后端基于 **Symfony (PHP)**，前端基于 **Vue.js**。

## 未来计划

- **改进**：我会不定期添加 Bug 修复、改进和新模块——只要是我个人需要的。
- **支持声明**：由于我有全职工作和个人事务，**无法保证提供技术支持**。本项目以 MIT 协议开源。欢迎提交 Issue 或提问，但我会优先开发我个人每天需要使用的功能。

## 贡献与鸣谢

- [查看贡献者列表](https://volmarg.github.io/personal-management-system-docs/docs/special-thanks.html)
