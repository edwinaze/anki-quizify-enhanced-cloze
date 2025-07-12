**在使用前，请仔细阅读本说明，下载链接位于文末。**

<img width="743" alt="word" src="https://github.com/user-attachments/assets/a174f425-9580-4aa8-8b81-4637a6f7c8d3" />

# Quizify (格致)：Anki 全能模板

> 《禮記·大學》：「欲誠其意者，先致其知，致知在格物。」

Quizify 是一个功能强大的 Anki 模板，支持多种交互式复习功能，如填空题、选择题、展开内容、注释弹窗等，旨在帮助您创建更灵活和动态的学习卡片，提升学习效率。

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

「格致」是 ”格物致知“ 的略语，以此命名模板主题有两层寓意：一是祝愿学习者能学有所成，在探索与实践中知行合一；二是希望大家在使用中感受到主题设计的格调与精致。整体布局延续了 [Prettify](https://github.com/pranavdeshai/anki-prettify) 的风格，配色大量采用了中国传统的复古色调。同时，主题遵循 WCAG 2.1 标准，确保文本色彩对比度符合易读性要求。（P.S. 未来可能会对主题样式适度调整，进一步提升视觉美感。）

默认字体列于下表，请用户自行获取，也可以在模板中的 CSS 样式中修改配置，换用其他字体。

|          | 主要字体     | 辅助字体     | 填空字体           |
| -------- | ------------ | ------------ | ------------------ |
| **中文** | 方正屏显雅宋 | 汉仪有楷 55W | 汉仪家书 55U       |
| **西文** | Georgia      | Sassoon Book | Sassoon Montessori |

## 📸 样例截图

<img width="530" alt="选择1" src="https://github.com/user-attachments/assets/ceca8a51-2176-47a0-9f2b-7291dbd9546a" />
<img width="530" alt="选择2" src="https://github.com/user-attachments/assets/3a5799df-1e61-4ab6-bc89-7e8d329cbd99" />
<img width="530" alt="选择3" src="https://github.com/user-attachments/assets/b5c1217b-cc64-4ac6-8cb8-7e0f061caca7" />
<img width="530" alt="选择4" src="https://github.com/user-attachments/assets/4a20f31b-27e1-4759-a05f-c3c552e7d0ab" />
<img width="521" alt="填空1" src="https://github.com/user-attachments/assets/cfb3f6dc-fd61-4462-af39-9ffe26bdb331" />
<img width="521" alt="填空2" src="https://github.com/user-attachments/assets/cd0a9cd0-2026-4891-962c-697a6a056f05" />
<img width="521" alt="填空3" src="https://github.com/user-attachments/assets/18b3a3d6-585c-4f27-ab91-b2997cbed68e" />
<img width="521" alt="填空4" src="https://github.com/user-attachments/assets/2fbaa76a-8b45-4c05-9309-fa42053dd861" />

## 🛠️ 安装方法

下载 [quizify.apkg](https://github.com/e-chehil/anki-quizify/blob/main/Deck/quizify.apkg) 文件导入 Anki。


# Enhanced Cloze 整合版：强化 Cloze 功能

基于 Quizify 原版设计推出了一个与 **Enhanced Cloze** 功能整合的特别版本，专为需要更强大填空功能的学习者设计。

## ✨ 核心特性
- **🎯 填空分类**：
  - **当前填空**：红色下划线标识，支持输入验证
  - **参考填空**：蓝色下划线标识，仅供参考
  - **已完成填空**：在当前填空序号之前的填空，自动显示为普通文本

- **⚡ 高效学习流程**：
  - 当前填空之前的内容自动显示，形成渐进式学习
  - 保留 Quizify 原版的所有除`选择题`的辅助功能（`折叠`、`隐藏`、`注释`）
  - 支持键盘快捷键操作

- **🎨 一致的视觉体验**：
  - 完全保留 Quizify 的优雅样式设计
  - 无缝集成输入验证和动画效果
  - 支持夜间模式和响应式布局

## 💡 适用场景
- 需要大量填空练习的学科（如语言学习、医学术语等）
- 希望结合上下文细粒度渐进学习的内容
- 需要同时展示相关概念的复习场景

## 操作介绍

### 鼠标操作

- 点击填空:
  - 当前填空: 显示输入框，可以输入答案
  - 其他填空: 切换显示/隐藏答案
- 点击屏幕左边缘: 揭示当前填空
- 点击屏幕右边缘: 揭示下一个 其他填空

点击左右侧边缘功能用于方便移动端使用。

### 键盘快捷键

- J: 揭示当前填空
- Shift+J: 隐藏当前填空
- N: 揭示下一个其他填空
- Shift+N: 显示/隐藏所有其他填空

### 输入验证

- 点击 当前填空 出现输入框
- 输入答案
- 按 Enter 或点击其他地方失去焦点
- 系统自动验证：
  - ✔ 正确答案显示绿色背景
  - ✘ 错误答案显示红色背景

## 细节修改

- 未回答的填空将统一设置为等长，不会有答案长度提示
- 字号均缩小2rem，因为该卡类型应用场景会有大量文字
- 卡片刚打开时页面将自动滑动到待填填空位置，后续揭示其他填空时也会将页面与之对齐
- 删去了 Enhanced Cloze v2.1 的额外信息功能，建议使用 Quizity 的注解格式

## 📸 样例展示

![QuizityWithEnhancedClozeGIF](https://github.com/user-attachments/assets/46612604-9e97-4f04-b194-d6bcdaa7ee7b)

## 🛠️ 安装方法

下载 [quizify-enhanced-cloze.apkg](https://github.com/e-chehil/anki-quizify/blob/main/Deck/quizify-enhanced-cloze.apkg) 文件导入 Anki。


## 🤝 开发贡献

如果您有改进建议或发现问题，欢迎提交 Issue 或 Pull Request！

如果您喜欢我的作品，可以通过以下方式予以支持：

- 在 GitHub 上为该项目**加注星标**
- **微信赞赏**

  <img src="https://github.com/user-attachments/assets/5d91de4c-8713-41ed-98e3-b53dd4562f30" width="400px" />
