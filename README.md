# 人生课题发现 Skill

一个用于 Codex、Kimi Code 等 AI 编程助手的对话式 Skill。

它不预测未来，也不替用户下人生结论。它会先阅读日记、笔记或人生经历，区分“发生了什么”和“我如何解释它”，再通过反例检验，帮助用户发现：

- 反复出现的行为模式
- 真正不能妥协的底线
- 用来理解世界的隐含模型
- 这个模型在哪些情况下会失效

## 怎么使用

安装后，在对话中输入：

> 开始发现自己的人生课题

也可以直接提供日记、笔记或一段人生经历，再说：

> 使用 discover-life-theme 分析这些材料。

AI 会分阶段提问，在证据不足时不会急着给结论。

## 安装

### 方法一：下载文件夹

1. 点击 GitHub 页面右上角的 **Code → Download ZIP**。
2. 解压下载的文件。
3. 把 `skills/discover-life-theme` 文件夹复制到：
   - 通用位置：`~/.agents/skills/`
   - 或 Codex 位置：`~/.codex/skills/`
4. 重启 AI 客户端或新建一个对话。

### 方法二：Codex 自动安装

在 Codex 中发送：

> 请从 GitHub 仓库 wuailin452-cmd/discover-life-theme 的 skills/discover-life-theme 路径安装这个 Skill。

## 隐私说明

仓库只包含 Skill 的方法和提示词，不包含作者的日记、个人案例、聊天记录、API Key 或其他私人数据。

## 边界

这个 Skill 用于自我反思与模式发现，不构成心理诊断、医疗建议、法律建议或确定性的人生预测。遇到危机或严重心理困扰时，应优先寻求专业支持。

## 目录

```text
skills/
└── discover-life-theme/
    ├── SKILL.md
    └── agents/
        └── openai.yaml
```

