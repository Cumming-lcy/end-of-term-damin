# Vibe Music Admin

<div align="center">
  <p>基于 Vue 3 + Vite + TypeScript 构建的音乐后台管理系统</p>
  <p>
    <img src="https://img.shields.io/badge/Vue-3.5-green" alt="Vue">
    <img src="https://img.shields.io/badge/Vite-6.0-purple" alt="Vite">
    <img src="https://img.shields.io/badge/Element_Plus-2.9-409EFF" alt="Element Plus">
    <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
  </p>
</div>

## 📖 简介

Vibe Music Admin 是音乐平台的后台管理系统，基于 [vue-pure-admin](https://github.com/pure-admin/vue-pure-admin) 开发，提供用户、歌手、歌曲、歌单、反馈和轮播图等核心管理功能。

## ✨ 功能特性

- 📊 **数据统计** - 实时展示用户、歌手、歌曲、歌单数量和趋势
- 👥 **用户管理** - 用户列表、详情查看、账号启停、头像上传
- 🎤 **歌手管理** - 歌手增删改查、分类筛选、批量操作
- 🎵 **歌曲管理** - 歌曲信息维护、音频/封面上传、标签分类
- 📝 **歌单管理** - 歌单创建编辑、歌曲关联、封面设置
- 💬 **反馈管理** - 用户反馈查看和处理
- 🖼️ **轮播图管理** - 首页轮播图配置和排序

## 🛠️ 技术栈

- **前端框架**: Vue 3.5 + Vite 6.0 + TypeScript 5.6
- **UI 组件**: Element Plus 2.9 + Tailwind CSS 3.4
- **状态管理**: Pinia 2.3 + Vue Router 4.5
- **HTTP 请求**: Axios 1.7
- **代码规范**: ESLint 9 + Prettier 3 + Stylelint 16
- **其他**: ECharts 5.5、cropperjs、dayjs

## 📋 环境要求

- **Node.js**: `^18.18.0 || ^20.9.0 || >=22.0.0`
- **pnpm**: `>=9`
- **后端服务**: [Vibe Music Server](https://github.com/Cumming-lcy/end-of-term) (需先启动)

## 🚀 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/Cumming-lcy/end-of-term.git
cd vibe-music-admin
```

### 2. 安装依赖

```bash
pnpm install
```

### 3. 启动开发服务

```bash
pnpm dev
```

访问: http://localhost:8089

**默认登录账号**:
- 用户名: `admin_1`
- 密码: `123456abc`

### 4. 构建生产版本

```bash
pnpm build
```

## 📜 常用命令

```bash
# 开发
pnpm dev              # 启动开发服务
pnpm build            # 构建生产版本
pnpm preview          # 预览构建结果

# 代码质量
pnpm lint             # 代码检查和格式化
pnpm typecheck        # TypeScript 类型检查
```

## 📷 项目截图

![登录界面](https://github.com/Cumming-lcy/end-of-term/blob/main/img/admin_login.png)
![系统首页](https://github.com/Cumming-lcy/end-of-term/blob/main/img/admin_home.png)
![用户管理](https://github.com/Cumming-lcy/end-of-term/blob/main/img/admin_user_management.png)

## 🔗 相关项目

- **后端服务**: [Vibe Music Server](https://github.com/Cumming-lcy/end-of-term)
- **项目模板**: [vue-pure-admin](https://github.com/pure-admin/vue-pure-admin)

## ⚠️ 免责声明

本项目仅供学习交流使用，请勿用于商业用途。使用者需自行承担使用风险，遵守相关法律法规和版权政策。

## 📜 许可证

本项目采用 MIT License 开源协议 - 查看 [LICENSE](LICENSE)

## ❤️ 贡献

欢迎提交 Issue 和 Pull Request！

## 👥 作者

**李钏洋** - [@Cumming-lcy](https://github.com/Cumming-lcy)

---

<div align="center">
  <p>如果这个项目对你有帮助，请给一个⭐Star支持一下！</p>
  <p>© 2024 Vibe Music Admin. Made with ❤️ by 李钏洋</p>
</div>
