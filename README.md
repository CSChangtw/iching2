# 易經多爻交互占測系統 v2 · PWA

六十四卦完整占測工具，含**卦辭、象傳、卦詩、推斷**四大欄位，支援多爻發動自動求之卦。
完全離線可用，可安裝至手機主畫面或桌面。

---

## 🚀 三步驟上架 GitHub Pages

### 1. 建立 Repository
[github.com](https://github.com) → **＋ → New repository**
- Name：`iching-pwa`（公開 Public）→ **Create**

### 2. 上傳全部檔案
進入 repo → **uploading an existing file** → 拖曳下列所有內容：
```
index.html
manifest.json
sw.js
icons/
  icon-72.png … icon-512.png
  apple-touch-icon.png
  favicon.ico
```
→ **Commit changes**

### 3. 啟用 Pages
**Settings → Pages → Branch: main / (root) → Save**

約 1 分鐘後網址生效：
```
https://你的帳號.github.io/iching-pwa/
```

---

## 📲 安裝為 App

| 平台 | 操作 |
|------|------|
| Android Chrome | 點畫面「安裝」橫幅，或選單→加入主畫面 |
| iOS Safari | 分享 ☐↑ → 加入主畫面 |
| 桌面 Chrome/Edge | 網址列右側 ⊕ 圖示 → 安裝 |

---

## ✨ v2 新增功能

- 【卦詩】每卦附民間七言詩，生動描繪運勢
- 【推斷】簡明四句斷語，涵蓋求財、婚姻、疾病、出行
- 按鈕文字改為「冥想事由、誠心起卦」，強調起卦前的靜心

---

## 🛠 本機測試

```bash
python3 -m http.server 8080
# 開啟 http://localhost:8080
```

*易經占測僅供參考，請以理性態度看待結果。*
