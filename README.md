# Seedance 2.x 中文提示词工程

面向 Seedance 2.x 的中文视频生成提示词 skill，覆盖多模态参考绑定、导演意图、可见表演、人物走位、镜头连续性、电商与服饰展示，以及可复现的提示词评测。

核心入口为 [`SKILL.md`](SKILL.md)，专项规则位于 [`references/`](references/)，Codex 界面元数据位于 [`agents/openai.yaml`](agents/openai.yaml)。

> 说明：本 skill 以 Seedance 2.0 已知引用方式为基础，不把第三方经验或未经证实的“2.5 规则”表述为官方模型规范。