# 郭奉先 · FengMr

**AI 应用工程师｜LLM 工作流、MCP 与语音交互｜React Native / Next.js 全栈研发与交付**

10 年软件研发经验，专长于前端与跨端开发，近期聚焦 AI 产品的完整交付。独立研发 IKI AI 日语学习产品及配套服务，参与 Writora 内容生产平台研发，曾参与去哪儿旅行 App 国际机票核心交易链路开发。

## 代表项目

| 项目 | 我的工作与工程重点 | 查看 |
| --- | --- | --- |
| **IKI AI** · AI 日语语音对话与学习产品 | 独立全栈研发及部署；语音交互、流式恢复、检索记忆与模型评测 | [产品](https://www.ikiai.org/) · [项目说明](projects/iki-ai.md) |
| **Writora** · AI SEO 内容生产平台 | 全栈研发；9 个 MCP 工具、多阶段内容生成、质量反馈与持久化任务 | [产品](https://www.writora.online/) · [项目说明](projects/writora.md) |
| **Local Voice Actions** · 端侧语音操作助手 | 个人项目，开发中，Demo 已验证；本机模型动作规划、严格校验与确定性工具执行 | [项目说明](projects/local-voice-actions.md) |

IKI AI 的配套 [Content Pipeline](projects/content-pipeline.md) 负责日语阅读内容的生成、审校、音频制作与发布。

以上项目源码保留在私有仓库，项目说明提供职责、处理流程和验证范围。

## 我关注的工程问题

- **让模型输出可控：** 通过 JSON Schema、Zod / Pydantic 与业务规则校验约束输出，将模型规划与工具执行分离。
- **让多阶段任务可恢复：** 处理请求取消、异步竞态、限次重试、持久化任务与版本化缓存，支持失败后的恢复执行。
- **让迭代有验证依据：** 使用开发集、冻结验证集和回归用例，结合输出合规、业务评分、费用与耗时评估方案。

## 开源贡献

| 项目 | 贡献 | 状态 |
| --- | --- | --- |
| **百度 amis** | 修复 Select 级联 / 分组模式的 `labelField` 丢失问题，以及条件组合组件自定义类型值不回显问题 | 已合并：[PR #6057](https://github.com/baidu/amis/pull/6057) · [PR #6165](https://github.com/baidu/amis/pull/6165) |
| **social-auto-upload** | 改进小红书视频上传状态检测，解决上传完成后持续等待的问题 | 已合并：[PR #193](https://github.com/dreammis/social-auto-upload/pull/193) |
| **Kestra** | 基于 Vue 3、AntV X6 提交工作流可视化 Demo 方案 | 方案 PR，未合并：[PR #843](https://github.com/kestra-io/kestra/pull/843) |

## 技术方向

- **AI 应用：** LLM API、MCP、结构化输出、Embedding / RAG、ASR / TTS、评测与工作流编排。
- **产品与服务：** TypeScript、React Native / Expo、React / Next.js、Vue、Python / FastAPI、PostgreSQL。
- **工程交付：** GitHub Actions、GitLab / Jenkins、Docker、Harbor、Kubernetes。

## 其他公开项目

[ByteBrief](https://github.com/KillenMr/bytebrief) 是使用 Next.js、React 与 Supabase 构建的科技简报阅读站，提供双资讯流、来源链接和往期归档。[在线查看](https://killenmr.github.io/bytebrief/)
