# Prompt Helper

## 简介
这是一个为开发者或非开发者提供日常工作提示模板的仓库。

## 快速开始
1. 复制提示文件内容。
2. 在Cursor中，使用快捷键**Command + K**打开**Composer**并粘贴内容。
3. 在**Composer**中**@**你想要重构的相关文件（包括测试文件）。
4. 在Cursor完成重构后，微调结果。

## 如何自定义提示
1. 在**Context**中添加你想关注的代码异味，例如长方法、长参数列表、重复代码、死代码等。
2. 梳理出代码味道的优先级，然后使用 ReAct 框架一一描述
3. 仔细规划每一步，并建立思维链（COT）以确保模型遵循你的预期操作。
4. 如果模型未按预期运行，请在**Constraint**部分添加自定义限制。

## 贡献
欢迎贡献！请遵循以下步骤：
1. Fork 仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个Pull Request

## 许可证
此项目使用MIT许可证。有关更多信息，请参阅LICENSE文件。
