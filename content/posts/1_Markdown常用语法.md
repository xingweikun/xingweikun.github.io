---
# 文章标题（中文）
title: "Markdown常用语法"
# 文章发布日期（中文格式）
date: 2025-03-25
# 文章分类（中文分类）
categories: ["Markdown"]
# 文章标签（中文标签）
tags: ["Markdown", "基础教程"]
# 文章是否为草稿状态
draft: false
# 文章SEO描述（中文）
description: "本文介绍Markdown常用语法，适合新手入门学习。"
---

Markdown教程网站推荐

[Markdown中文网站](https://www.markdown.cn/ "点击进入")


## 一、基础排版语法
### 1. 标题层级
```markdown
# H1标题
## H2标题
### H3标题
#### H4标题
##### H5标题
###### H6标题
```
预览效果：
# H1标题  
## H2标题  
### H3标题  
#### H4标题  
##### H5标题  
###### H6标题  

### 2. 文本强调
| 语法示例              | 预览效果            |
|-----------------------|-------------------|
| `**粗体**`            | **粗体**          |
| `*斜体*`              | *斜体*            |
| `***粗斜体***`        | ***粗斜体***      |
| `~~删除线~~`          | ~~删除线~~        |


## 二、结构化元素
### 1. 列表系统
```markdown
- 无序列表项
   - 嵌套子项  
1. 有序列表项
   1. 嵌套编号 
```
预览效果：  
- 无序列表项
  - 嵌套子项

1. 有序列表项
   1. 嵌套编号  


### 2. 引用区块
```markdown
> 主引用内容
> > 嵌套引用
> > - 带列表的引用
```
预览效果：  
> 主引用内容
> > 嵌套引用
> > - 带列表的引用  


### 3. 表格制作
```markdown
| 左对齐 | 居中对齐 | 右对齐 |
|:-------|:--------:|-------:|
| A      |    B     |     C | 
```
预览效果：  
| 左对齐 | 居中对齐 | 右对齐 |
|:-------|:--------:|-------:|
| A      |    B     |     C |  


## 三、代码
### 1. 代码展示
`` `print("行内代码")` `` 

三个`加编程语言(python或java等)
```python
def fibonacci(n):
    if n <= 1:
        return n
    else:
        return fibonacci(n-1) + fibonacci(n-2)
```

预览效果：  
`print("行内代码")`  
```python
def fibonacci(n):
    if n <= 1:
        return n
    else:
        return fibonacci(n-1) + fibonacci(n-2)
```  


## 四、扩展功能
### 1. 任务列表
```markdown
- [x] 已完成
- [ ] 待办事项
```
预览效果：  
- [x] 已完成  
- [ ] 待办事项  


## 五、多媒体管理
### 1. 图片插入
```markdown
![本地图片](images/logo.png) 
![网络图片](https://via.placeholder.com/200x50?text=示例图片)
```
预览效果：  
![示例图片](https://via.placeholder.com/200x50?text=示例图片)


### 基础链接语法
#### 1. **行内式链接**（最常用）
```markdown
[显示文本](链接地址 "悬浮提示")
```
• **示例**：  
  `[访问百度](https://www.baidu.com "国内搜索引擎")`  
  *效果：* [访问百度](https://www.baidu.com "国内搜索引擎")  
  *说明*：双引号内为鼠标悬停时显示的提示文字，可省略

---

### 二、特殊链接类型
#### 3. **自动链接**（快速生成）
```markdown
<https://example.com>
<user@example.com>
```
• **效果**：  
  <https://example.com>  
  <user@example.com>  
  *特点*：自动识别 URL 和邮箱

---

### 三、进阶技巧
#### 5. **本地文件链接**
```markdown
[下载文档](./docs/manual.pdf)
```
• *注意*：需确保文件路径正确

#### 6. **格式化链接**
```markdown
[**重要通知**](http://example.com/alert)
[`API文档`](/api/v2)
```
• **效果**：  
  [**重要通知**](http://example.com/alert)  
  [`API文档`](/api/v2)  
  *扩展*：支持粗体、代码块等样式

---

### 四、兼容性最佳实践
1. **空格处理**：链接中的空格需替换为 `%20`（如 `http://example.com/path%20with%20space`）
2. **跨平台验证**：在微信公众号等平台发布前，需测试链接是否可点击
3. **链接管理**：超过 5 个重复链接时建议使用引用式

---

**示例整合**：
```markdown
欢迎访问[我的博客](https://blog.example.com)，查看最新[技术文章](/posts)。  
相关资源：  
- 联系邮箱：<contact@example.com>  
- [下载 PDF 手册](./docs/guide.pdf)  
```

*效果预览*：  
欢迎访问[我的博客](https://blog.example.com)，查看最新[技术文章](/posts)。  
相关资源：  
• 联系邮箱：<contact@example.com>  
• [下载 PDF 手册](./docs/guide.pdf)
