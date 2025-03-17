# Jixiv - Android图片分享应用

<p align="center">
  <img src="https://img.shields.io/badge/平台-Android-brightgreen" alt="平台" />
  <img src="https://img.shields.io/badge/语言-Kotlin-orange" alt="语言" />
  <img src="https://img.shields.io/badge/架构-MVVM-blue" alt="架构" />
  <img src="https://img.shields.io/badge/许可证-MIT-green" alt="许可证" />
</p>

## 📱 项目介绍

Jixiv是一款基于Android开发的图片分享应用，类似于Pixiv的移动客户端。应用采用Material Design设计风格，提供流畅的用户体验，支持图片浏览、收藏、分享等功能。

## ✨ 主要功能

- **用户系统**：支持用户注册、登录、个人资料管理
- **图片浏览**：支持多种分类浏览和搜索功能
- **收藏系统**：用户可以收藏喜欢的图片并进行管理
- **社交功能**：支持用户关注、私信和评论互动
- **创作中心**：用户可以上传和管理自己的作品
- **离线模式**：支持图片缓存，实现离线浏览功能

## 🛠️ 技术栈

- **开发语言**：Kotlin
- **架构模式**：MVVM (Model-View-ViewModel)
- **UI框架**：Material Design Components
- **网络请求**：Retrofit + OkHttp
- **图片加载**：Glide
- **本地存储**：Room Database
- **依赖注入**：Hilt
- **异步处理**：Kotlin Coroutines + Flow
- **导航组件**：Jetpack Navigation

## 📋 系统要求

- Android 6.0 (API级别23)或更高版本
- 至少2GB RAM
- 至少100MB可用存储空间

## 📲 安装方法

1. 从[Release页面](https://github.com/Ghostenpower/jixiv/releases)下载最新APK
2. 在Android设备上启用"未知来源"应用安装权限
3. 点击下载的APK文件进行安装

或者从源码构建：

```bash
# 克隆仓库
git clone https://github.com/Ghostenpower/jixiv.git

# 进入项目目录
cd jixiv

# 使用Gradle构建
./gradlew assembleDebug
```

## 🖼️ 应用截图

<p align="center">
  <img src="screenshots/home.png" width="200" alt="首页" />
  <img src="screenshots/detail.png" width="200" alt="详情页" />
  <img src="screenshots/profile.png" width="200" alt="个人中心" />
</p>

## 🔮 未来计划

- [ ] 添加深色模式支持
- [ ] 实现AI推荐系统
- [ ] 增加更多图片滤镜效果
- [ ] 支持视频内容
- [ ] 优化离线体验

## 🤝 贡献指南

欢迎贡献代码、报告问题或提出新功能建议！请遵循以下步骤：

1. Fork本仓库
2. 创建您的特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交您的更改 (`git commit -m '添加一些很棒的功能'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 开启一个Pull Request

## 📄 许可证

本项目采用MIT许可证 - 详情请查看[LICENSE](LICENSE)文件

## 📞 联系方式

如有任何问题或建议，请通过以下方式联系我：

- GitHub Issues: [https://github.com/Ghostenpower/jixiv/issues](https://github.com/Ghostenpower/jixiv/issues)
- Email: [your-email@example.com](2315181588@qq.com)

---

<p align="center">
  使用 ❤️ 由 Ghostenpower 开发
</p>
