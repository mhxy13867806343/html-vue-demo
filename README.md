# 前端示例项目集合

[在线预览](https://mhxy13867806343.github.io/html-vue-demo/)

该项目包含多个前端演示示例，展示各种数据可视化和交互功能。

## 项目内容

### 本地演示项目

1. **选手数据排行 (hero-stats.html)**
   - 展示选手的击杀参与率、比赛胜率、死亡率等数据
   - 支持按位置分类查看选手数据
   - 数据可视化展示，带有颜色编码的统计图表

2. **电竞赛事对阵图 (tournament-bracket.html)**
   - 展示多轮比赛的对战结果和晋级路线
   - 包含比赛时间、队伍信息和比分
   - 直观的树形结构表示比赛流程

### 项目结构

```
vue-focus/
├── index.html          # 项目导航页
├── hero-stats.html     # 选手数据统计页面
├── tournament-bracket.html  # 比赛对阵图页面
├── hero.js             # 选手数据
└── README.md           # 项目说明
```

## 技术栈

- Vue 3.2
- Element Plus 2.3.12
- 原生JavaScript

## 使用说明

1. 克隆仓库到本地
   ```bash
   git clone https://github.com/mhxy13867806343/html-vue-demo.git
   ```

2. 直接在浏览器中打开index.html即可访问项目导航页
   - 从导航页可以进入各个演示项目
   - 也可以直接打开各个HTML文件查看对应功能

## 数据来源

项目中的数据存储在本地的hero.js文件中，包含选手的各项统计数据，如击杀、助攻、死亡等信息。

## 特点

- 无需后端服务器，纯前端实现
- 响应式设计，适配不同屏幕尺寸
- 直观的数据可视化
- 模块化的代码结构

## 贡献

欢迎提交Issue或Pull Request改进项目。

## 联系方式

- **GitHub主页**：[https://github.com/mhxy13867806343](https://github.com/mhxy13867806343)
- **邮箱**：[869710179@qq.com](mailto:869710179@qq.com)

## 许可

MIT License

```
Copyright (c) 2025 mhxy13867806343

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
