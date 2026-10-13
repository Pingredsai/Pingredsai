# Pingredsai

---

## 🇬🇧 English

I build **on-device AI** — language models that run entirely on a phone.
No cloud. No API keys. No data leaving the device.

### Currently

**[LocalAI](https://github.com/Pingredsai/local-ai-android)** — a fully offline LLM chat app for Android
(llama.cpp + JNI + Jetpack Compose, MIT licensed).

Measured on a Google Pixel 4 (Snapdragon 855, 2019) with Qwen2.5-1.5B Q4_K_M:

| Metric | Result |
|---|---|
| Generation | **18.5 tok/s** |
| First token | **52 ms** |
| Memory | ~1.3 GB |
| Network permission | **none** |

The app's manifest does not request `INTERNET` at all.

### What I work on

- **On-device / mobile LLM inference** — llama.cpp, GGUF, ARM optimisation
- **Android** — Kotlin, Jetpack Compose, JNI/NDK, CMake
- **Local & private LLM deployment** — RAG, knowledge bases, air-gapped setups
- **Performance debugging** — and I write up what I find

### Writing

Debugging notes from the trenches:

1. *Why Your Phone Runs LLMs 80x Slower Than It Should* — the missing `-march`
2. *Threads on Big Cores, CPU at Full Clock — Still Slow* — ruling out scheduling and frequency scaling
3. *Is Your Phone's LLM 37x Too Slow?* — the `-O0` build trap

Read them on [DEV](https://dev.to/pingredsai).

### Open to

Freelance work on **on-device AI** and **local LLM integration** —
especially where data cannot leave the device
(legal, healthcare, finance, air-gapped environments).

If you're building something in this space, I'd like to hear about it.

---

## 🇨🇳 中文

我专注**端侧 AI** —— 让大模型真正跑在手机上，不联网、不调 API、数据不出设备。

### 当前项目

**[LocalAI](https://github.com/Pingredsai/local-ai-android)** —— 一个完全离线的 Android 大模型对话应用
（llama.cpp + JNI + Jetpack Compose，MIT 开源）。

在 Google Pixel 4（骁龙 855，2019）上用 Qwen2.5-1.5B Q4_K_M 实测：

| 指标 | 结果 |
|---|---|
| 生成速度 | **18.5 tok/s** |
| 首 token 延迟 | **52 ms** |
| 内存占用 | ~1.3 GB |
| 联网权限 | **无**（manifest 里根本没申请 `INTERNET`） |

### 我做什么

- **端侧 / 移动端大模型推理** —— llama.cpp、GGUF、ARM 优化
- **Android 开发** —— Kotlin、Jetpack Compose、JNI/NDK、CMake
- **本地化 / 私有化 LLM 部署** —— RAG、知识库、内网隔离环境
- **性能排查** —— 并且把过程和踩过的坑写成文章

### 技术文章

1. 《为什么你的手机跑 LLM 比别人慢 80 倍》—— 交叉编译时缺失的 `-march`
2. 《线程在大核、CPU 满频，为什么还是慢？》—— 用排除法否定调度与降频
3. 《手机跑大模型慢 37 倍？检查一下这个编译选项》—— Debug 构建的 `-O0` 陷阱

欢迎在 [掘金](https://juejin.cn/user/1350638568746430) 上阅读。

### 可承接

承接**端侧 AI** 与**本地化大模型部署**相关的外包与咨询，
尤其是数据不能出设备的场景（法律、医疗、财税、制造、涉密单位）。

如果你正在做这方面的东西，欢迎交流。

---

## 📫 联系 / Contact

**邮箱**：siquhjh@gmail.com

**微信**：扫码添加（请说明来意）

<p align="center">
  <img src="wechat.png" width="380" alt="微信二维码">
</p>

> 承接 **端侧 AI** 与 **本地化大模型部署** 相关的外包与咨询。
> 也欢迎纯粹的技术交流 —— 不一定要有项目。