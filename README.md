# 个人学术主页

这是一个简洁美观的个人学术主页，用于展示个人教育背景、研究方向、发表论文等学术信息。

## 项目结构

```
yixiaobei/
├── index.html      # 主页面HTML文件
├── styles.css      # 样式表文件
└── README.md       # 项目说明文档
```

## 功能特点

- **响应式设计**：适配不同屏幕尺寸，在桌面端和移动端都有良好的显示效果
- **现代美观的UI**：采用卡片式设计，搭配平滑的过渡动画和悬停效果
- **清晰的信息架构**：包含以下主要模块：
  - 个人简介
  - 教育背景
  - 研究方向
  - 发表论文
  - 联系方式

## 使用方法

### 查看页面

直接在浏览器中打开 `index.html` 文件即可查看个人学术主页。

### 修改内容

1. **修改基本信息**：编辑 `index.html` 文件中的相应部分
2. **调整样式**：修改 `styles.css` 文件中的CSS规则
3. **添加或删除论文**：在 `index.html` 文件的 `publications-list` 中添加或删除 `publication-item` 元素
4. **调整研究方向**：在 `index.html` 文件的 `research-grid` 中添加或删除 `research-item` 元素

## 技术栈

- **HTML5**：页面结构
- **CSS3**：样式设计，包括Grid布局、Flex布局、过渡动画等
- **Font Awesome**：图标库
- **Git**：版本控制

## 自定义指南

### 修改配色方案

在 `styles.css` 文件中修改CSS变量：

```css
:root {
    --primary-color: #2c5aa0;      /* 主色调 */
    --secondary-color: #4a90e2;    /* 次要色调 */
    --accent-color: #e74c3c;       /* 强调色 */
    /* 其他颜色变量 */
}
```

### 添加新的研究方向

在 `index.html` 文件中添加新的 `research-item` 元素：

```html
<div class="research-item">
    <div class="research-icon">
        <i class="fas fa-icon-name"></i> <!-- 替换为合适的图标 -->
    </div>
    <h3>研究方向名称</h3>
    <p>研究方向描述...</p>
</div>
```

### 添加新的论文

在 `index.html` 文件中添加新的 `publication-item` 元素：

```html
<div class="publication-item">
    <h3>论文标题</h3>
    <p class="journal">期刊名称, 年份, 卷(期): 页码范围.</p>
    <p class="authors">作者1, 作者2, 作者3, et al.</p>
</div>
```

## 版本控制

项目使用Git进行版本控制，主要提交历史：

- 初始提交：创建个人学术主页
- 添加研究论文：增加到6篇研究论文
- 调整布局：优化研究方向与论文部分的对齐

## 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 许可证

MIT License
