# Quizify (格致)：Anki 全能模板

> 《禮記·大學》：「欲誠其意者，先致其知，致知在格物。」

Quizify 是一个功能强大的 Anki 模板，支持多种交互式学习功能，如填空题、选择题、展开内容、注释弹窗等，旨在帮助您创建更灵活和动态的学习卡片，提升学习效率。

## 🌟功能模块

- **📝 内容折叠/展开**: 点击标题折叠或展开详细内容。
  - **格式**: `[[标题::详细内容]]`

- **🔒 文段隐藏/揭示**: 点击提示显示隐藏文段，支持再次隐藏。
  - **格式**: `((提示::隐藏文段))`

- **💬 弹出注释**: 点击文字，弹出注释气泡框，点击任意位置关闭注释。
  - **格式**: `[文字]^(注释内容)`

- **✏️ 填空题**: 支持用户输入答案并提供正误反馈。
  - **格式**: `{{填空答案}}`

- **✅ 选择题**: 支持单选和多选题，提供答案随机化与正误标识。
  - **格式**: `[选项内容]::(正确选项)`


## 💡 交互细节

- **⌨️ 快捷键：**
  - 通过 `Tab` 键可对功能模块进行全局导航。
  - 通过 `Control` 键可快速触发交互对象。
    - 填空题显示输入框
    - 选择题勾选选项
    - 验证选择题答案
    - 展开/折叠内容
    - 显示/隐藏文段
    - 弹出/关闭注释
- **👀 视觉提示**:
  - 填空题作答反馈不同的正误状态（`✔` 或 `✘`）。
  - 选择题标记正确（绿）、错误（红）、未选项（黄）等状态。
- **🎲 选项随机化**: 
  - 确保选项每次随机排列，避免熟悉选项顺序。
  - 查看选择题答案时会恢复原题序号，方便对照解析。



## 🎨 主题风格

「格致」是 ”格物致知“ 的略语，以此命名模板主题有两层寓意：一方面寓意着学习者能学有所成，在探索与实践中知行合一；二是希望大家在使用中感受到主题设计的格调与精致。整体布局延续了 [Prettify](https://github.com/pranavdeshai/anki-prettify) 的风格，配色大量采用了中国传统的复古色调。同时，主题遵循 WCAG 2.1 标准，确保文本色彩对比度符合易读性要求。（P.S. 未来可能会对主题样式适度调整，进一步提升视觉美感。）

默认字体列于下表，请用户自行获取，也可以在模板中的 CSS 样式中修改配置，换用其他字体。

|          | 主要字体     | 辅助字体     | 填空字体           |
| -------- | ------------ | ------------ | ------------------ |
| **中文** | 方正屏显雅宋 | 汉仪有楷 55W | 汉仪家书 55U       |
| **西文** | Georgia      | Sassoon Book | Sassoon Montessori |

## 📸 样例截图

<img width="521" alt="填空1" src="https://github.com/user-attachments/assets/cfb3f6dc-fd61-4462-af39-9ffe26bdb331" />
<img width="521" alt="填空2" src="https://github.com/user-attachments/assets/cd0a9cd0-2026-4891-962c-697a6a056f05" />
<img width="521" alt="填空3" src="https://github.com/user-attachments/assets/18b3a3d6-585c-4f27-ab91-b2997cbed68e" />
<img width="521" alt="填空4" src="https://github.com/user-attachments/assets/2fbaa76a-8b45-4c05-9309-fa42053dd861" />
<img width="521" alt="选择1" src="https://github.com/user-attachments/assets/2aecb47a-5097-449b-84d5-6a4c55d2db76" />
<img width="521" alt="选择2" src="https://github.com/user-attachments/assets/e655611a-46c3-4d39-9000-3fa819143629" />
<img width="521" alt="选择3" src="https://github.com/user-attachments/assets/28f6496f-cdfd-4ad8-bf17-fe004c7ae758" />
<img width="521" alt="选择4" src="https://github.com/user-attachments/assets/c8fda1cd-29bf-4004-b694-ce3cbb5c005b" />

## 🛠️ 安装方法

下载 [quizify.apkg](https://github.com/e-chehil/anki-quizify/blob/main/Deck/quizify.apkg) 文件导入 Anki。

## 🤝 开发贡献

如果您有改进建议或发现问题，欢迎提交 Issue 或 Pull Request！

如果您喜欢我的作品，可以通过以下方式予以支持：

- 在 GitHub 上为该项目**加注星标**
- **微信赞赏**

  <img src="https://github.com/user-attachments/assets/5d91de4c-8713-41ed-98e3-b53dd4562f30" width="400px" />
