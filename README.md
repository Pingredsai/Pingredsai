# Pingredsai

I build **local-first AI systems** — models and knowledge tools that run on your own device or infrastructure.

我专注 **本地优先 AI** —— 让模型和知识工具运行在用户自己的设备或内网里。

---

## 🇬🇧 English

### Featured projects

#### [LocalRAG](https://github.com/Pingredsai/local-rag) — private document Q&A

A self-hosted knowledge base that answers questions from your own documents.

- FastAPI + Qdrant + Ollama
- Local `bge-m3` embeddings and local LLM generation
- Answers include source references
- Runs without cloud AI APIs after initial setup
- Docker Compose deployment
- MIT licensed, `v0.1.0` verified end to end

[Repository](https://github.com/Pingredsai/local-rag) · [Release](https://github.com/Pingredsai/local-rag/releases/tag/v0.1.0) · [Demo video](https://github.com/Pingredsai/local-rag/blob/main/demo/video/localrag-demo.mp4)

![LocalRAG answer with sources](localrag.png)

#### [LocalAI](https://github.com/Pingredsai/local-ai-android) — fully offline LLM on Android

A local LLM app for Android with no `INTERNET` permission at all.

Measured on a Google Pixel 4 with Qwen2.5-1.5B Q4_K_M:

| Metric | Result |
|---|---|
| Generation | **18.5 tok/s** |
| First token | **52 ms** |
| Memory | ~1.3 GB |
| Network permission | **none** |

### What I work on

- On-device and mobile LLM inference
- Private, self-hosted RAG and knowledge bases
- Local model deployment for privacy-sensitive environments
- Android, Kotlin, JNI/NDK, FastAPI, Docker
- Performance debugging and practical engineering notes

### Writing and contact

I write about local AI deployment, on-device inference, and performance debugging:

- [DEV](https://dev.to/pingredsai)
- [Juejin](https://juejin.cn/user/1350638568746430)

I’m open to **freelance work and POCs** involving on-device AI, private RAG, local LLM deployment, and air-gapped environments.

---

## 🇨🇳 中文

### 代表项目

#### [LocalRAG](https://github.com/Pingredsai/local-rag) —— 私有化文档知识库问答

把你的文档放进自己的服务器，让 AI 基于资料回答问题，并返回来源引用。

- FastAPI + Qdrant + Ollama
- 本地 `bge-m3` 向量化 + 本地大模型生成
- 回答附带来源，便于追溯
- 初始化完成后，运行时不依赖云端 AI API
- 支持 Docker Compose 部署
- MIT 开源，`v0.1.0` 已完成端到端验证

[项目仓库](https://github.com/Pingredsai/local-rag) · [版本发布](https://github.com/Pingredsai/local-rag/releases/tag/v0.1.0) · [演示视频](https://github.com/Pingredsai/local-rag/blob/main/demo/video/localrag-demo.mp4)

![LocalRAG 回答与来源](localrag.png)

#### [LocalAI](https://github.com/Pingredsai/local-ai-android) —— 完全离线的 Android 本地大模型

Android 端本地运行大模型，安装包里没有申请任何联网权限。

在 Google Pixel 4 上使用 Qwen2.5-1.5B Q4_K_M 实测：

| 指标 | 结果 |
|---|---|
| 生成速度 | **18.5 tok/s** |
| 首 token | **52 ms** |
| 内存 | ~1.3 GB |
| 联网权限 | **无** |

### 我做什么

- 端侧 / 移动端大模型推理
- 私有化 RAG 与本地知识库
- 数据不能出内网的本地模型部署
- Android、Kotlin、JNI/NDK、FastAPI、Docker
- 性能排查与工程实践记录

### 内容与联系

我主要写本地 AI 部署、端侧推理和性能排查相关内容：

- [掘金](https://juejin.cn/user/1350638568746430)
- [DEV](https://dev.to/pingredsai)

可承接 **端侧 AI、私有化 RAG、本地大模型部署和涉密环境交付**相关的项目、POC 与技术咨询。

---

## 📫 Contact

**Email**: siquhjh@gmail.com

**微信**: 扫码添加（请说明来意）

<p align="center">
  <img src="wechat.png" width="380" alt="微信二维码">
</p>

> 端侧 AI / 私有化 RAG / 本地模型部署。
> 也欢迎纯粹的技术交流。