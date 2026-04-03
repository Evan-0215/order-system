# 线下发单系统

基于腾讯云CloudBase的订单管理系统，支持：
- 发货解析
- 库存管理
- 出货对账
- 多客户管理

## 部署到Vercel（免费，推荐）

### 方式一：拖拽上传（最简单）

1. 访问 https://vercel.com/new
2. 选择"Upload Files"或直接拖拽整个文件夹
3. 等待部署完成
4. 访问 https://tpttoy.vercel.app

### 方式二：使用Vercel CLI

```bash
# 安装Vercel CLI
npm i -g vercel

# 进入项目目录
cd c:/Users/Svan/CodeBuddy/线上发单系统

# 部署
vercel --prod
```

### 绑定自定义域名

1. 在Vercel项目设置 → Domains
2. 添加域名：tpttoy.com 或 tpttoy.fun
3. 按照提示配置DNS记录

## 本地运行

直接用浏览器打开 `index.html` 即可

## 技术栈

- 纯HTML/CSS/JavaScript
- 腾讯云CloudBase（可选）
- ExcelJS（数据导出）

## 数据存储

- 本地：localStorage
- 云端：CloudBase（需配置环境ID）
