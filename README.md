
# 🎧 Audio-Ops-Agents

> **将音乐学专业理论与互联网运营逻辑深度融合的 AI 智能体套件。**

本项目致力于利用 AI 技术解决音频运营、短视频 BGM 匹配及音乐科技流转中的痛点。通过结构化的提示词工程（Prompt Engineering），将感性的艺术需求转化为理性的技术规格。

---

### ⚙️ 核心处理逻辑 (Logic Flow)

```mermaid
graph LR
    A[视频场景描述] --> B{意境解构}
    B --> C[音乐学参数定义]
    C --> D[AI Prompt 生成]
    D --> E[运营与后期建议]
    
    style B fill:#f9f,stroke:#333,stroke-width:2px
    style D fill:#bbf,stroke:#333,stroke-width:2px
````

-----

## 🌟 核心智能体 (Core Agents)

### 🎹 BGM 情绪匹配专家 (BGM Mood Specialist)

  - **位置**: `agents/bgm-mood-specialist.md`
  - **功能**: 输入视频描述，输出精准的 **BPM**、**调式**、**配器建议**以及 **Suno/Udio 生成指令**。
  - **价值**: 弥补视觉意蕴与音频生产之间的技术鸿沟，为内容运营提供专业音频落地支撑。
  - **实战演示**: [📂 点击查看：古装仙侠剧预告片案例](./examples/case-wuxia-cinematic.md)
-----

## 🛠️ 快速开始

1.  **获取指令**：进入 `agents/` 目录，找到对应的 `.md` 文件并复制全部内容。
2.  **激活 Agent**：将内容作为 **System Prompt** 发送给 AI 助手（如 Gemini, ChatGPT 或 Claude）。
3.  **输入需求**：描述你的业务场景（例如：*“制作一个 20 岁女性受众的清冷香水广告”*），获取专业音频方案。

-----

## 📈 项目路线图 (Roadmap)

  - [x] **v1.0 发布**：上线 BGM 情绪匹配专家及首个实战案例。
  - [ ] **v1.1 规划**：开发「英文曲库自动化标签清洗专家」。
  - [ ] **v1.2 规划**：完善「AI 音乐科技中英文术语对照表」。
  - [ ] **v2.0 愿景**：探索 DAW (Logic Pro / Cubase) 自动化工作流集成。

-----

## 🤝 贡献与反馈

欢迎 Fork 本项目！如果你有更好的音频运营思路或 Prompt 优化建议，请提交 Pull Request。

**Maintainer**: [DawnnnHuang](https://github.com/DawnnnHuang)
**License**: MIT
