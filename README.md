# AIRSPACE AI 商品貼標系統

## 快速啟動

### 1. 設定 API Key
```bash
export ANTHROPIC_API_KEY=sk-ant-你的API金鑰
```

### 2. 啟動伺服器
```bash
node server.js
```

### 3. 開啟瀏覽器
```
http://localhost:3000
```

---

## 部署到 Render.com（免費）

1. 把這個資料夾上傳到 GitHub
2. 到 https://render.com 新增 Web Service
3. 連接你的 GitHub repo
4. 設定環境變數：`ANTHROPIC_API_KEY = sk-ant-你的金鑰`
5. Start Command 填：`node server.js`
6. 完成！取得公開網址分享給大家

## 部署到 Railway.app（免費）

```bash
npm install -g @railway/cli
railway login
railway init
railway up
railway variables set ANTHROPIC_API_KEY=sk-ant-你的金鑰
```

## 部署到 Zeabur（台灣）

1. https://zeabur.com 新增專案
2. 部署 GitHub repo
3. 設定環境變數 ANTHROPIC_API_KEY
4. 完成

---

## 功能

- 拖曳 / 點擊 / Ctrl+V 上傳圖片
- 輸入商品圖片網址
- AI 分析四大維度（結構、辣度、特色、導購）
- 支線適配評分（AS / CHIC.A / LADY / A+）
- 信心值 < 80% 自動標注待審核
- 銷售潛力評估
- 一鍵匯出貼標紀錄 .txt
- 標籤資料庫瀏覽
- 暢銷滯銷分析
- 導購文案範例
- 升級至 100 分改款建議

