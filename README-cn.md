# 🚀 作品集 — 自由职业接单展示

> 📖 [English Version](README.md)

一套为自由职业者准备的可直接部署的 Portfolio 样本，展示你作为 **AI-Native 开发者** 的技能。

## 🌐 在线预览

| 样本 | 在线预览 | 适用场景 |
|------|---------|---------|
| 🚀 **落地页** | [🔗 在线预览](https://xia-shangzhou.github.io/portfolio/sample1-landing-page-cn/) | Fiverr/Upwork 展示、客户提案 |
| 📊 **管理后台** | [🔗 在线预览](https://xia-shangzhou.github.io/portfolio/sample2-saas-dashboard-cn/) | SaaS 项目展示、后台系统演示 |
| 🔍 **代码审计** | [🔗 在线预览](https://xia-shangzhou.github.io/portfolio/sample3-fix-ai-code-cn/) | 修复 AI 代码服务展示 |

## 📁 文件结构

```
portfolio-samples/
├── sample1-landing-page-cn/     # 中文落地页
├── sample2-saas-dashboard-cn/   # 中文管理后台
├── sample3-fix-ai-code-cn/      # 中文代码审计
├── sample1-landing-page/        # 英文落地页
├── sample2-saas-dashboard/      # 英文管理后台
├── sample3-fix-ai-code/         # 英文代码审计
├── fiverr-gigs.md              # Fiverr 服务描述模板
├── upwork-profile.md           # Upwork 个人主页文案
└── quick-start-plan.md         # 快速启动计划
```

## 💡 服务报价

| 服务 | 我的报价 | 传统报价 | 优势 |
|------|---------|---------|------|
| 落地页 | ¥1,500-¥3,500 | ¥5,000-¥15,000 | 便宜 60%，快 3 倍 |
| 企业官网 | ¥3,500-¥10,000 | ¥15,000-¥35,000 | 便宜 65%，快 4 倍 |
| 管理后台 | ¥5,500-¥18,000 | ¥20,000-¥60,000 | 便宜 68%，快 3 倍 |
| 代码审计修复 | ¥1,000-¥4,000 | ¥3,500-¥15,000 | 便宜 70%，快 5 倍 |

## 📋 接单话术

**当客户问工具时：**
> ✅ "我用现代全栈技术栈（React/Next.js），配合自动化工具加速开发，所以能比传统开发快 3-5 倍交付。"

**当客户问为什么便宜时：**
> ✅ "我专注于标准化项目（落地页、官网、后台），有成熟的开发流程，效率更高，不牺牲质量。"

**当客户要看作品时：**
> ✅ "当然！这是我最近的项目：[链接1] [链接2] [链接3]，都是 48 小时内交付的。"

## 📝 国内接单平台

| 平台 | 特点 | 推荐度 |
|------|------|--------|
| **程序员客栈** | 国内中高端，平台派单，项目均价 3-5万 | ⭐⭐⭐⭐⭐ |
| **飞援** | 远程灵活用工，有审核，结算有保障 | ⭐⭐⭐⭐ |
| **猪八戒** | 老牌平台，单价低，适合练手 | ⭐⭐ |

## 🚀 部署方式

### GitHub Pages（免费）
```bash
cd portfolio-samples
git init && git add . && git commit -m "Portfolio"
git remote add origin https://github.com/你的用户名/portfolio.git
git push -u origin main
# 在 Settings → Pages 开启 GitHub Pages
```

### Vercel（免费，更快）
```bash
npm i -g vercel
cd portfolio-samples/sample1-landing-page-cn
vercel --prod
```

### 宝塔面板（你的 VPS）
1. 上传文件到 `/www/wwwroot/你的域名/`
2. 宝塔 → 网站 → 设置 → 伪静态
3. 添加规则：
```nginx
location / {
    try_files $uri $uri/ /index.html;
}
```

## 📚 相关文档

- [Fiverr 服务描述模板](fiverr-gigs.md)
- [Upwork 个人主页文案](upwork-profile.md)
- [快速启动计划](quick-start-plan.md)
