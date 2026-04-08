# LCPlus# LCPlus - LinkedClassroom 界面美化

一个纯 CSS 的学校系统界面优化工具，不修改任何功能，不读取任何数据，只让页面更好看。

---

## ✨ 效果

- 统一蓝灰色主题，减少刺眼白色
- 课程菜单居中悬浮弹窗
- 修复弹窗被遮挡问题
- 课程卡片、侧边栏、导航栏风格统一

---

## 🔧 技术实现

| 项目 | 说明 |
|------|------|
| 语言 | 纯 CSS |
| 加载方式 | 书签小工具 / 浏览器插件 |
| 分发 | jsDelivr CDN + GitHub |
| 更新 | 修改 CSS 后自动生效 |

---

## 🚀 使用方法（30秒）

1. 在浏览器书签栏**新建书签**
2. 名称填写：`美化学校`
3. 网址填写下方代码（**整段复制**）：

```javascript
javascript:(function(){let link=document.createElement('link');link.rel='stylesheet';link.href='https://cdn.jsdelivr.net/gh/zha-chicken/LCPlus/main.css';document.head.appendChild(link);alert('✅ LC+ACTIVATED');})();
