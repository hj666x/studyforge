# StudyForge - 学习引擎

专升本·考研一站式学习规划与打卡工具

## 功能

- 📅 每日打卡 + 连续天数统计
- 📋 专升本/考研三阶段学习计划
- 📚 视频课程、教材、真题资源推荐
- 🏫 目标院校信息（含官网/报名链接）
- 📜 证书报名官网汇总
- ⏱️ 学习计时器
- 📖 单词背诵系统（60个考研核心词）
- ➕ 自定义课程管理
- 🤖 AI学习助手
- 📊 学习数据分析
- 💾 数据导出/备份

## 部署方式

### 方式1：GitHub Pages（推荐，免费永久）

1. 创建 GitHub 仓库
2. 上传 `index.html`、`manifest.json`、`sw.js`
3. Settings → Pages → Source: Deploy from branch → main
4. 访问 `https://你的用户名.github.io/仓库名/`

### 方式2：Vercel（免费，速度快）

1. 访问 vercel.com
2. Import Git Repository
3. 自动部署

### 方式3：Netlify（免费）

1. 访问 netlify.com
2. 拖拽文件夹部署

### 方式4：本地使用

直接用浏览器打开 `index.html` 即可

## 手机安装（PWA）

1. 部署后用手机浏览器访问
2. Safari: 分享 → 添加到主屏幕
3. Chrome: 菜单 → 添加到主屏幕
4. 即可像APP一样使用

## 数据存储

所有数据存储在浏览器 localStorage 中，不会上传到任何服务器。
支持数据导出备份（设置 → 导出数据）。
