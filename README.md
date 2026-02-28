# COSMO V3 数据采集表单

产品诊断数据采集前端，支持模式A（Sorftime分析）和模式B（全量诊断）。

## 部署到 GitHub Pages

### 方式一：命令行（推荐）

```bash
# 1. 创建仓库（建议 Private）
gh repo create cosmo-v3-form --private

# 2. 初始化并推送
cd cosmo-v3-form
git init
git add .
git commit -m "init: COSMO V3 数据采集表单"
git branch -M main
git remote add origin git@github.com:你的用户名/cosmo-v3-form.git
git push -u origin main

# 3. 开启 GitHub Pages
#    GitHub 仓库 → Settings → Pages → Source: Deploy from a branch → main / root → Save
```

### 方式二：GitHub Desktop

1. 把 `cosmo-v3-form` 文件夹拖进 GitHub Desktop
2. Publish → 勾选 Private
3. 到 GitHub 仓库 Settings → Pages → main branch → Save

### 访问地址

部署后约1分钟生效：
```
https://你的用户名.github.io/cosmo-v3-form/
```

> ⚠️ GitHub Pages 即使仓库是 Private，页面仍然是**公开可访问**的（需要Pro/Team/Enterprise才能私有Pages）。
> 如果需要密码保护，可以在 index.html 顶部加一个简单的密码验证层。

## 技术栈

- 纯 HTML + CSS + Vanilla JS（零依赖）
- 响应式设计，支持手机/平板
- 暗色科技风主题
