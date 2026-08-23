<p align="right">
  <a href="./README.md">English</a>
</p>

<h1 align="center">你好，我是 yanghui1-arch 👋</h1>

<p align="center">
  计算机专业 · 开源贡献者 · 大模型系统与 AI 应用
</p>

## 关于我

- 🎓 上海大学计算机专业硕士三年级在读
- 🏫 南昌大学计算机专业本科
- 🔭 关注大模型推理、AI Agent、可观测性与全栈系统
- 🌱 喜欢从真实问题出发，为开源项目提交专注且经过验证的改进

## 开源贡献

### [vLLM](https://github.com/vllm-project/vllm)

主要参与模型执行、CUDA Graph 正确性、推测解码、结构化输出和模型兼容性相关工作。

| PR | 状态 / 角色 | 贡献内容 |
|---|---|---|
| [#51113](https://github.com/vllm-project/vllm/pull/51113) | 已合并 · 共同作者 | 保持 Mamba align prefill chunk 在 `last_cache_position` 之后仍按 block 对齐 |
| [#47861](https://github.com/vllm-project/vllm/pull/47861) | 已关闭 · 作者 | 修复混合 Mamba 模型的 MTP prefix cache 正确性问题 |
| [#38640](https://github.com/vllm-project/vllm/pull/38640) | 已关闭 · 作者 | 修复流式工具调用最终 chunk 中 type 或 ID 为空的问题 |
| [#38010](https://github.com/vllm-project/vllm/pull/38010) | 已关闭 · 作者 | 修复 GLM-4.1V/4.6V-Flash 的 BitsAndBytes 量化问题 |
| [#37873](https://github.com/vllm-project/vllm/pull/37873) | 已合并 · 作者 | 修复 CUDA Graph 填充区域中的 RoBERTa `position_id` 累积问题 |
| [#37507](https://github.com/vllm-project/vllm/pull/37507) | 已关闭 · 作者 | 为旧版 CUDA 工具链的 GDN prefill 增加回退路径 |

### [AionUI](https://github.com/iOfficeAI/AionUi)

主要参与 Agent 集成、ACP 稳定性、聊天体验和界面健壮性相关工作。

| PR | 状态 / 角色 | 贡献内容 |
|---|---|---|
| [#804](https://github.com/iOfficeAI/AionUi/pull/804) | 已合并 · 作者 | 集成 nanobot |
| [#784](https://github.com/iOfficeAI/AionUi/pull/784) | 已关闭 · 作者 | 防止 ACP Agent 后端未定义 |
| [#568](https://github.com/iOfficeAI/AionUi/pull/568) | 已关闭 · 作者 | 改善回复延迟与前几次发送消息丢失的问题 |
| [#550](https://github.com/iOfficeAI/AionUi/pull/550) | 已合并 · 作者 | 修复超长内容溢出区块的问题 |

### [AIRI](https://github.com/moeru-ai/airi)

4 个 PR 均已合并，主要改进语音服务兼容性和网页端音色选择体验。

| PR | 状态 / 角色 | 贡献内容 |
|---|---|---|
| [#593](https://github.com/moeru-ai/airi/pull/593) | 已合并 · 作者 | 正确显示音色搜索结果 |
| [#579](https://github.com/moeru-ai/airi/pull/579) | 已合并 · 作者 | 修复 OpenAI 与 CosyVoice v2 的音色测试 |
| [#576](https://github.com/moeru-ai/airi/pull/576) | 已合并 · 作者 | 增加 CosyVoice SSML 支持 |
| [#568](https://github.com/moeru-ai/airi/pull/568) | 已合并 · 作者 | 修复语音模块中的 CosyVoice v1 测试 |

## 我的项目

### [mwin](https://github.com/yanghui1-arch/mwin) · [Cloudflare 在线体验](https://aitrace-cloudflare-backend.mwin-172f8144.workers.dev)

一个开源的大模型可观测性平台，可追踪 OpenAI、Claude、Gemini 及兼容 OpenAI 接口的模型。项目包含 Python SDK、Web 控制台，以及 Java 与 Cloudflare 后端，帮助开发者查看 Trace Tree、分析延迟与成本，并持续改进 Agent 系统。

`Python` · `TypeScript` · `Java` · `React` · `Cloudflare Workers` · `D1`

---

<p align="center">
  <a href="https://github.com/yanghui1-arch">GitHub</a>
</p>

