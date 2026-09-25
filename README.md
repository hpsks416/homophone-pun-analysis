# homophone-pun-analysis

为语言学实验提供一套可复用的框架，用于**识别、标注、分类、生成**「谐音梗 / 神翻译」类样本，并量化其语义漂移与情感反转。

## 环境依赖

- 操作系统：Windows
- 运行时：无（纯指令型 skill，由 agent 直接执行）
- 第三方软件：无（仅依赖系统自带的 PowerShell / 标准库）

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
