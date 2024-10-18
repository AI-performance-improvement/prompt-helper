# prompt-helper

## Introduction
This is a repository providing daily work prompt templates for developers or non-developers.

## Quick Start
1. Copy the content of the prompt file.
2. In Cursor, use the shortcut **Command + K** to open the **Composer** and paste the content.
3. @ the relevant files you want to refactor in the **Composer** (including test files).
4. Fine-tune the results after Cursor completes the refactoring.

## How to Customize Prompts
1. Add the code smells you want to focus on in the **Context**, such as long methods, long parameter lists, duplicate code, dead code, etc.
2. Sort out the priority of the code smell, then use ReAct framework to describe it one by one
3. Carefully plan each step and establish a Chain of Thought (COT) to ensure the model follows your intended operations.
4. If the model does not operate as expected, add custom constraints in the **Constraint** section.

## Contribution
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License. For more information, please refer to the LICENSE file.