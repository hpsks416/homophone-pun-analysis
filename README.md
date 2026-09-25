# homophone-pun-analysis

为语言学实验提供一套可复用的框架，用于**识别、标注、分类、生成**「谐音梗 / 神翻译」类样本，并量化其语义漂移与情感反转。

## 适用对象

- DeepSeek Harness（DSH）用户：一个可由 AI agent 按需自动加载的 skill，克隆即用、无需构建。
- 做语言学实验（谐音梗/神翻译样本标注与生成）的研究者

## 目录结构

    homophone-pun-analysis/
    ├── SKILL.md    技能入口与工作流

## 安装

    # GitHub
    git clone https://github.com/hpsks416/homophone-pun-analysis.git "$env:USERPROFILE\.dsh\skills\homophone-pun-analysis"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/homophone-pun-analysis.git "$env:USERPROFILE\.dsh\skills\homophone-pun-analysis"

克隆后 DSH 自动重新发现，无需构建。

## License

MIT License. See [LICENSE](LICENSE).
