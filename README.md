# Parcel Optimizer

📦 自動拆包計算器 - 幫助你用最省運費的方式合併寄送多件貨物。

## 功能特色

- 支援「最佳模式」：遍歷所有可能組合，找出最低總運費
- 支援「快速模式」：使用啟發式分組，快速取得接近最省方案
- 可自訂：
  - 每公斤運費
  - 每單最大重量
  - 低重量加收派送費條件
- 顯示每單小計、總花費與計算時間

## 使用方式

```bash
npm install
npm run dev
```

開啟瀏覽器至 `http://localhost:5173`

## 部署建議

推薦使用 [Vercel](https://vercel.com) 部署：
1. 將此專案推上 GitHub
2. 登入 Vercel 並點選「New Project」
3. 選取此 repo，點選 Deploy 即可
