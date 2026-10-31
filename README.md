# 👋 你好，我是 soyoung5565

学生开发者，专注 **Android 开发 / AI 应用** 方向 —— 喜欢把想法打磨成真实可用的产品：从端侧 AI Agent 到课堂翻译 App，从 AI 家教系统到语音识别评测。

**技术栈**：Kotlin · Jetpack Compose · Flutter · Python · LLM 应用开发 · ASR / 语音

---

## 🚀 主力项目

### 🧠 [myagent](https://github.com/soyoung5565/myagent) — 端侧 AI Agent（Android）
在设备上运行、像人一样操作手机的 AI Agent：无障碍服务 + 视觉模型理解屏幕，自动完成 App 操作任务。基于 OpenOmniBot 的融合开发版，自研 **+52,523 行**（Agent 核心、记忆系统等模块重写）。
`Kotlin` `Flutter` `Android` `AI Agent`

### 🎙 [classroom-translator](https://github.com/soyoung5565/classroom-translator) — 课堂实时翻译 App
实时课堂翻译：三引擎可切换 ASR（云端流式 / 本地离线 / 分片回退）+ LLM 翻译，双语卡片即时呈现；课后整课录音转写。**85 个提交**的完整开发轨迹，从设计稿到真机像素级还原。
`Kotlin` `Jetpack Compose` `WebSocket` `LLM` `ASR`

### 📚 [family-tutor](https://github.com/soyoung5565/family-tutor) — AI 家庭教师系统
面向小学三科的完整教学闭环：按知识点出卷 → 两阶段批改（先让学生自己找错）→ 错题微课堂。含 **1.2 万+ 题**的题库与建设工具链。
`Python` `LLM` `OCR` `教育`

### 🎧 [asr-evaluation](https://github.com/soyoung5565/asr-evaluation) — ASR 模型评测与本地部署
面向马来西亚口音 / 中英混说场景：**5 个模型 × 3 个测试集（1453 句真人音频）** 横向评测；WSL2 + vLLM 流式部署与整课转录服务。
`ASR` `Benchmark` `vLLM` `Whisper` `Qwen`

---

## 🔧 工具合集

**[toolbox](https://github.com/soyoung5565/toolbox)** — 一组独立开发的小工具与自动化脚本：
`电商客服 Agent` `AI 提词器` `屏幕实时翻译` `游戏挂机自动化` `多模态理解工具` `API 格式代理`

---

## 📦 可复用组件

**[llm-provider-kit](https://github.com/soyoung5565/llm-provider-kit)** — LLM 接入工具库（TypeScript，44 个测试）：
数据驱动的 Provider 注册表 · Anthropic 兼容端点鉴权 · 有界并发池 · Windows 安全原子写

---

## 🌱 开源二次开发

这两个是在上游开源项目基础上做的二次开发，**README 里写清楚了我具体改了什么**：

- **[ApkClaw](https://github.com/soyoung5565/ApkClaw)** → **MyClaw** —— 手机里的 AI 助手。84 文件 / +5816 行改动：自定义 LLM Provider 与思考深度控制、全渠道实时日志系统、配置服务扩展（新增剪贴板 / 完整 UI 树 / 滚动查找等工具）、微信官方渠道接入、密钥编译期注入。
- **[OpenOmniBot](https://github.com/omnimind-ai/OpenOmniBot)** → **[myagent](https://github.com/soyoung5565/myagent)** —— 端侧 AI Agent。自研 5.2 万行，重写 Agent 核心、记忆系统、Codex 集成。

---

## 🧰 我的工程习惯

- **不把密钥写进源码** —— 编译期注入（`local.properties` → `BuildConfig`），并用 `git filter-repo` 清过全历史
- **不吹数字** —— README 里的准确率、色差、迭代次数都来自实测报告，可复现
- **先验证再汇报** —— 交付物跑一遍再提交，测试报告用真机数据而不是估计值

---

*📌 持续打磨中，欢迎交流。*
