# 盯盘助手 App

## 功能
- A股、美股、港股、黄金实时行情
- 技术指标（MACD、RSI、均线）
- 主力资金流向
- 最新市场资讯
- AI深度分析（Claude驱动）

## 安装到手机/桌面（PWA方式）

### 方法一：部署到 GitHub Pages（免费，推荐）

1. 在 GitHub 新建仓库，如 `stock-watcher`
2. 把这个文件夹里的所有文件上传到仓库
3. 进入仓库 Settings → Pages → Source 选 main 分支
4. 访问 `https://你的用户名.github.io/stock-watcher/`

### 手机安装（iOS）
1. 用 Safari 打开上述网址
2. 点底部分享按钮 → "添加到主屏幕"
3. 像 App 一样从桌面打开

### 手机安装（Android）
1. 用 Chrome 打开网址
2. 点右上角菜单 → "添加到主屏幕" 或 "安装应用"

### 电脑安装
1. 用 Chrome/Edge 打开网址
2. 地址栏右侧出现安装图标，点击安装
3. 或菜单 → "安装盯盘助手"

---

## 本地运行（开发用）

```bash
# 用任意静态服务器
npx serve .
# 或
python3 -m http.server 8080
```

访问 http://localhost:8080

---

注：价格数据为演示数据，AI分析功能需要 Anthropic API Key（在生产版本中配置）。
