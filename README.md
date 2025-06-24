# 🚀 永恒

> 一个探索/试验性质的自学服务中心，致力于为学生提供优质的自学资源

<style>
/* 表格样式 - 深色优雅风格 */
table {
  border-collapse: collapse;
  width: auto;
  margin: 20px 0;
  background: #1a1a1a;
  border: 1px solid #333;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
  font-size: 14px;
  outline:solid 2px #fff2;
}

th {
  background: #2d2d2d;
  color: #e0e0e0;
  font-weight: 600;
  padding: 14px 18px;
  text-align: left;
  border-bottom: 1px solid #2a2a2a;
  border-right: 1px solid #333;
  font-size: 13px;
  text-transform: none;
  letter-spacing: 0.5px;
}

th:last-child {
  border-right: none;
}

td {
  padding: 14px 18px;
  border-bottom: 1px solid #2a2a2a;
  border-right: 1px solid #333;
  color: #d0d0d0;
  transition: background-color 0.3s ease;
  white-space: nowrap;
}

td:last-child {
  border-right: none;
}

td:first-child {
  background: #252525;
  color: #f0f0f0;
  font-weight: 600;
  text-shadow: none;
}

tr:hover td {
  background: #2a2a2a;
  transform: none;
}

tr:hover td:first-child {
  background: #303030;
}

tr:last-child td {
  border-bottom: none;
}

/* 代码块样式 */
code {
  background: #2d2d2d;
  color: #00d4aa;
  padding: 2px 6px;
  border-radius: 4px;
  font-family: 'SFMono-Regular', Consolas, 'Liberation Mono', Menlo, monospace;
  border: 1px solid #404040;
  font-size: 13px;
}

/* 链接样式 */
a {
  color: #4a9eff;
  text-decoration: none;
  transition: color 0.3s ease;
}

a:hover {
  color: #66b3ff;
  text-shadow: none;
}
</style>

## 🚀 快速开始

### 环境要求

- Node.js >= 18.16.1
- npm >= 9.0.0

### 安装步骤

1. **克隆项目**

   ```bash
   git clone https://github.com/suyangzuo/suyangzuo.github.io.git
   cd suyangzuo.github.io
   ```

2. **安装依赖**

   ```bash
   npm install
   ```

3. **启动开发服务器**

   ```bash
   npm run live
   ```

4. **访问应用**

   打开浏览器访问 [http://localhost:3000](http://localhost:3000)

### 生产部署

项目支持多种部署方式：

- **Vercel**: 自动部署，支持 GitHub 集成
- **Render**: 云平台部署，支持自动构建
- **腾讯云**: 传统服务器部署

## 👨‍💻 开发指南

### 开发环境配置

1. **代码格式化**

   项目使用 Prettier 进行代码格式化，配置在`package.json`中：

   ```json
   {
     "prettier": {
       "printWidth": 120
     }
   }
   ```

2. **热重载开发**

   使用 nodemon 实现开发环境热重载：

   ```bash
   npm run live
   ```

### 代码规范

- 使用中文变量名和函数名，提高代码可读性
- 遵循 HTML5 语义化标签规范
- CSS 采用 BEM 命名规范
- JavaScript 使用 ES6+语法特性

### 文件组织

- **静态资源**: 所有静态文件放在`public`目录下
- **模块化**: 每个功能模块独立目录
- **资源分类**: 图片、脚本、样式分别存放

## 🤝 贡献指南

我们欢迎所有形式的贡献！

### 贡献方式

1. **提交 Issue**: 报告 bug 或提出新功能建议
2. **提交 PR**: 修复 bug 或添加新功能
3. **完善文档**: 改进项目文档
4. **分享经验**: 在博客中分享技术经验

### 贡献流程

1. Fork 项目
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

## 📄 许可证

本项目采用 [MIT License](LICENSE) 许可证。

## 🎉 致谢

### 设计资源

- **永恒 Logo**: 由同事"氯化银"原创设计
- **图片资源**: 大部分图片资源来自互联网，版权归原作者所有

### 技术资源

- **Font Awesome**: 提供丰富的图标资源
- **Google Fonts**: 提供优质字体服务
- **Express**: 提供强大的 Web 框架
- **开源社区**: 提供各种开源工具和库

## 📞 联系我们

- **GitHub**: [https://github.com/suyangzuo](https://github.com/suyangzuo)
- **网站**: [https://suyangzuo.com](https://suyangzuo.com)
- **邮箱**: 通过 GitHub Issues 联系

---

⭐ 如果这个项目对你有帮助，请给我们一个 Star！

## 🎯 功能模块

| 模块              | 类型       | 特色功能                       | 技术栈          |
| ----------------- | ---------- | ------------------------------ | --------------- |
| **📝 经验之谈**   | 重博客     | 原创文章、图文并茂、代码实例   | HTML/CSS/JS     |
| **📚 知识库**     | 轻博客     | Markdown、实时预览、代码高亮   | Markdown/JS     |
| **🎮 交互式学习** | 可视化平台 | 实时交互、多领域覆盖、统一界面 | CSS/JS/Canvas   |
| **🎯 休闲游戏**   | 游戏集合   | 经典游戏、益智游戏、学习结合   | HTML5/Canvas/JS |
| **🔬 Web 应用**   | 应用展示   | 密码生成、随机选择、快捷键测试 | Vanilla JS      |
| **💾 软件下载**   | 资源聚合   | 开发工具、数据库、设计软件     | 静态资源        |

### 🎮 交互式学习中心 - 核心模块

| 类别           | 数量 | 核心功能                                 |
| -------------- | ---- | ---------------------------------------- |
| **CSS 可视化** | 12+  | Box-Model、Flex、Grid、Transform         |
| **数据结构**   | 6+   | Array、Stack、Queue、LinkedList          |
| **算法可视化** | 4+   | Bubble-Sort、Selection-Sort、Insert-Sort |
| **前端技术**   | 8+   | CSS-Selector、Filter、Clip-Path          |

### 🎯 休闲游戏 - 游戏类型

| 类型         | 数量 | 代表作品                   |
| ------------ | ---- | -------------------------- |
| **经典游戏** | 4+   | 俄罗斯方块、贪吃蛇、打砖块 |
| **益智游戏** | 3+   | 汉诺塔、找炸弹、猜人物     |
| **休闲娱乐** | 2+   | 石头剪刀布、投掷石头       |

## 📄 信息页面

| 页面            | 类型     | 功能                         |
| --------------- | -------- | ---------------------------- |
| **👥 贡献者**   | 团队介绍 | 成员展示、技能展示、联系方式 |
| **🎯 网站宗旨** | 项目理念 | 项目定位、开发初衷、目标用户 |

### 🎯 网站宗旨 - 核心理念

| 维度         | 内容                                       |
| ------------ | ------------------------------------------ |
| **项目定位** | 探索/试验性质的自学服务中心                |
| **开发初衷** | 降低优质资源搜索难度，节省宝贵时间         |
| **目标用户** | 学生、初学者、寻找优质教程资源的入门开发者 |
| **维护团队** | 职业学校教师主导，多位朋友/同事参与贡献    |
| **反馈渠道** | GitHub Discussions、邮件等多种反馈方式     |
