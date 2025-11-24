# GitHub Pages 部署指南

## 🚀 快速部署

### 1. 上传代码到GitHub

```bash
# 进入项目目录
cd github-deployment

# 初始化Git仓库
git init

# 添加所有文件
git add .

# 创建提交
git commit -m "解开心结训练营 - 东方奢雅·水墨禅意版"

# 添加远程仓库（替换为您的仓库地址）
git remote add origin https://github.com/您的用户名/仓库名.git

# 推送到GitHub
git push -u origin main
```

### 2. 启用GitHub Pages

1. 访问您的GitHub仓库
2. 点击 Settings 标签
3. 在左侧菜单中找到 Pages
4. Source 选择 "Deploy from a branch"
5. Branch 选择 "main"
6. Folder 选择 "/ (root)"
7. 点击 Save 保存

### 3. 访问您的网站

部署完成后，访问：
```
https://您的用户名.github.io/仓库名
```

## 📁 文件说明

- `index.html` - 主页面（完整响应式设计）
- `assets/images/` - 图片资源文件夹
- `docs/` - 项目文档（PDF、设计说明、总结）
- `README.md` - 项目说明文档
- `.gitignore` - Git忽略文件配置

## 🎨 设计特色

- **水墨禅意风格**：东方美学与现代设计的完美融合
- **响应式布局**：完美适配所有设备
- **文化元素**：中文数字、书法感字体、禅宗留白
- **专业标准**：WCAG AAA无障碍认证

## 📞 技术支持

如需帮助，请查阅 `README.md` 文件或联系开发团队。

---
*部署时间：2025-11-24*
*版本：v2.0 水墨禅意版*