# OpenAniBT

OpenAniBT 是致力于为动漫爱好者、字幕组与开发者打造现代化内容分发与检索体验的开源组织。

我们构建了围绕 [anibt.net](https://anibt.net) 的全套技术生态，涵盖现代化的资源发布与检索中枢、专为二次元审美定制的前端设计系统，以及自动化数据管线。

- 生产站点：[anibt.net](https://anibt.net)
- 知识库与使用指南：[wiki.anibt.net](https://wiki.anibt.net)
- 设计系统与组件库：[ui.anibt.net](https://ui.anibt.net)

---

## 立项背景

长久以来，动漫 BT 资源与字幕组内容分发多依赖于传统老旧架构与简陋论坛，普遍存在以下痛点：

1. **检索与追踪效率低下**：缺乏语义化元数据与现代化搜索引擎支持，用户在海量散落的资源中难以高效追踪特定番剧、季度或版本。
2. **字幕组协同流程繁琐**：缺少规范的团队权限控制、自动化发布模板与跨站点分发工具，发布流程高度依赖手动操作且易错。
3. **架构封闭且体验割裂**：平台普遍闭源，缺乏标准化开放接口，社区难以在其基础上构建下游自动化工作流与衍生工具。

OpenAniBT 的立项旨在改变这一现状——**以现代软件工程标准重塑中文动漫资源基础设施**。在保证极速、开放、高可用的同时，提供兼具设计美感与专业易用性的全栈解决方案。

---

## 项目矩阵与生态说明

### 1. AniBT Core / Web
面向动漫 BT 资源与字幕组工作流的主干发布、聚合与检索系统。
- 技术栈：TanStack Start、TanStack Query、React、PostgreSQL、Bun Runtime、Typesense、Redis
- 核心功能：
  - 基于 Typesense 的毫秒级全文检索与番剧时间线智能聚合
  - 字幕组团队入驻、权限管理、发布模板与多站点同步 API
  - 自动化的 Torrent、MediaInfo 解析与封面处理管线
  - 高性能 SSR 缓存与分布式可观测性

### 2. AniBT UI ([OpenAniBT/ui](https://github.com/OpenAniBT/ui))
专为动漫与 ACG 站点打造的「贴纸手账」风格前端设计系统与组件库。
- 架构形态：基于 Tailwind CSS v4 与 Radix UI 的 shadcn registry（`@anibt` 命名空间），源码直落项目，零黑盒依赖。
- 视觉风格：模切白边、糖果光泽、和纸胶带与缝线质感，支持「白樱」（亮色）与「夜樱」（暗色）双色体系。
- 演示与文档：[ui.anibt.net](https://ui.anibt.net)

### 3. AniBT RSS & 数据管线
面向番剧追踪与自动化订阅服务的数据处理中枢。
- 提供标准化 RSS 提要输出、自动化番剧追新识别、外站发布监听与元数据补全服务。

---

## 核心理念

- **极简专注**：拒绝过度广告与视觉噪点，专注纯粹的内容检索与极速浏览体验。
- **尊重协同**：为字幕组提供规范、安全的协作工具与开放 API，降低发布与分发成本。
- **开放共建**：拥抱现代 Web 标准与开源生态，向社区持续开放组件库与开发者工具。

---

## 参与共建

欢迎通过 GitHub 关注各仓库进展、提交 Issue 反馈或发起 Pull Request。

- 组织仓库列表：[github.com/OpenAniBT](https://github.com/OpenAniBT)
- 官方使用指南：[wiki.anibt.net](https://wiki.anibt.net)
