# homophone-pun-analysis

分析或生成中文谐音梗与跨语言"神翻译"（同音/近音替换导致的语义漂移与情感反转），用于语言学实验的样本标注、机制归类与生成。触发词：谐音梗、神翻译、跨服聊天、音近替换、AI has made RAM more expensive、爱让记忆变得更加珍贵。

## 这是什么

DSH（DeepSeek Harness）skill —— 一个可由 AI agent 按需自动加载的能力单元。克隆到 skill 目录后，DSH 会依据上方描述自动发现并触发它，无需构建。

## 安装

最简单：用 [dsh-config](https://github.com/hpsks416/dsh-config) 的一键脚本 `install.ps1` 批量安装全部 skill。单个安装：

    # GitHub
    git clone https://github.com/hpsks416/homophone-pun-analysis.git "$env:USERPROFILE\.dsh\skills\homophone-pun-analysis"
    # 或 Gitee（国内直连更快）
    git clone https://gitee.com/hpsks416/homophone-pun-analysis.git "$env:USERPROFILE\.dsh\skills\homophone-pun-analysis"

克隆后 DSH 会自动重新发现，无需重启。更新用：

    git -C "$env:USERPROFILE\.dsh\skills\homophone-pun-analysis" pull

## 目录结构

    homophone-pun-analysis/
    ├── SKILL.md    技能入口与工作流
    （无附加文件，纯指令型 skill）

## 依赖

无运行时依赖，纯指令型 skill（由 agent 直接执行 Markdown 工作流）。

## License

MIT License. See [LICENSE](LICENSE).
