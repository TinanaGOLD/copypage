# 🌸 话术助手 - 你的沟通效率小帮手

&gt; ✨ 让重复的话术一键复制，让沟通更轻松～


---

## 🎀 项目介绍

**话术助手**是一个专为客服、运营、销售等需要频繁沟通的小伙伴设计的轻量级话术管理工具！💼

每天要和不同用户重复说同样的话？打字打到手酸？😫  
把常用话术保存在这里，**一键复制**，效率翻倍！🚀

无需下载安装，打开网页就能用，数据自动保存在本地，刷新也不丢失～

---

## 🌟 功能亮点

### 📝 话术管理
- **快速添加**：在输入框敲入话术，回车或点击按钮立即保存
- **一键复制**：点击复制按钮，话术瞬间进入剪贴板，还带可爱的"✅ 已复制"反馈哦
- **双击/长按编辑**：电脑双击，手机长按，轻松修改或删除话术

### 📂 智能分组
- **默认分组**："全部"看所有，"未分组"放临时话术
- **自定义分组**：按场景创建分组（比如"售前咨询"、"售后服务"、"常见问题"）
- **分组编辑**：双击分组名即可重命名或删除，话术自动归类到"未分组"

### 💾 数据持久化
- 所有数据保存在浏览器 `localStorage` 中
- 关闭页面、刷新浏览器，数据都在！
- 首次使用还有温馨的引导页面～

### 📱 完美适配
- 响应式设计，手机、平板、电脑都能用
- 移动端优化触摸交互（长按、双击）
- 可爱的粉红色系 UI，看着就心情好！

---

## 🎮 在线体验

👉 **[点击立即体验](https://tinanagold.github.io/copypage/)** 👈

无需注册，打开即用！建议添加到手机主屏幕，像 App 一样使用～

---

## 🛠️ 技术栈

| 技术 | 说明 |
|:---:|:---|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | 语义化标签构建页面结构 |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Flexbox + Grid 布局，CSS 变量管理主题色 |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | 原生 ES6+，无框架依赖 |
| ![LocalStorage](https://img.shields.io/badge/LocalStorage-ff6b9d?style=flat-square) | 本地数据持久化存储 |

**特色实现：**
- 🎨 **CSS 架构**：BEM 命名规范，模块化的样式设计
- 📲 **触摸事件**：自定义 `touchstart/touchend` 实现移动端长按/双击
- 🎯 **性能优化**：事件委托、防抖处理、被动事件监听
- ♿ **无障碍**：语义化标签、键盘导航支持、焦点管理

---

## 🚀 快速开始

### 本地运行
```bash
# 克隆仓库
git clone https://github.com/tinanagold/copypage.git

# 进入目录
cd copypage

# 用浏览器打开（或者使用本地服务器）
open index.html
# 或者
python -m http.server 8000
