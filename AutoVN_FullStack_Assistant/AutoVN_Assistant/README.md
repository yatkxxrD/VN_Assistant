# Visual Novel (Galgame) 全栈自动化助手

## 目录结构
- `core_engine.py`: 主程序，负责调度脚本生成与资源分配。
- `config.json`: 项目配置，包括路径和API密钥。
- `prompt_templates.txt`: 预设的AI调优提示词。

## 使用说明
1. 确保安装了 Ren'Py 引擎。
2. 配置 `config.json` 中的项目名称。
3. 运行 `python core_engine.py`。
4. 程序将自动创建 Ren'Py 兼容的目录结构并生成初始 `script.rpy`。

## 后续扩展
- 对接 Stable Diffusion API 实现自动立绘生成。
- 对接 GPT-SoVITS 实现角色自动配音。
