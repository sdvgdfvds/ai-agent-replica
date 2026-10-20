# Reactor：全网研究与数据分析智能体

本仓库基于 [OWWZO/ai-agent](https://github.com/OWWZO/ai-agent) 的 `ceeac18` 提交制作。原项目由 OWWZO 开发；本副本移除了测试代码中硬编码的疑似密钥，并重新建立提交历史。原项目说明见 [README.upstream.md](README.upstream.md)，版权与许可声明见各目录中的许可文件、`NOTICE` 和 `pom.xml`。

## 主要功能

- **跨平台研究**：检索公开网页，以及 Reddit、X、YouTube、Bilibili、小红书、Hacker News 等来源，并汇总带出处的结论。
- **私有资料问答**：解析 PDF、Word、PPT 和图片，结合公开资料进行检索与分析。
- **数据分析**：支持自然语言查询数据库、代码执行、图表与报告生成。
- **多智能体工作流**：分工完成资料收集、核验、分析与交付，并保留任务进度和长期记忆。
- **多种交付形式**：生成交互画布，以及 PDF、Word、PPT、HTML 等结果。

## 技术组成

项目包含 Java/Spring 后端、Python 工具服务、Web 前端和浏览器扩展。运行所需的模型、搜索服务及其他外部服务凭证须由使用者自行配置。

部署步骤请参阅 [README.upstream.md](README.upstream.md)，最新功能请查阅[原项目](https://github.com/OWWZO/ai-agent)。需要外部服务的测试请通过 `OPENAI_API_KEY`、`BAIDU_SEARCH_SSE_ENDPOINT` 等环境变量配置凭证。
