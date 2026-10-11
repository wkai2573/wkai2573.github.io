# 炸蝦 🍤 · 作品集

> 我是炸蝦，小小開發者。做興趣主導的專案，沒有用特定的技術。一切都問 AI，好愛 Agent。

🌐 **線上訪問**：[https://wkai2573.github.io/](https://wkai2573.github.io/)

---

## 🎮 精選專案列表

| 專案名稱 | 類型與技術棧 | 線上體驗 | 核心技術亮點 |
| :--- | :--- | :--- | :--- |
| **守燈人 · The Lamplighter** | 2.5D Atmospheric Adventure<br>`Three.js` `WebGL` `Web Audio` `Bun` | [🎮 開啟遊玩](https://wkai2573.github.io/lamplighter/) | 窄視角透視真實 3D 視差、解析積分自製霧氣體積散射、Karplus-Strong 撥弦生成式配樂、約 780 KB 極速啟動 |
| **雨夜便利商店與秋夜旅館** | WebGL Miniature Scenes<br>`Three.js` `GLSL` `SSAO` `Spatial Audio` | [👀 進入場景](https://wkai2573.github.io/3d-miniature-scenes/) | 三渲二（Toon Shader＋描邊）與 SSAO 環境光遮蔽、動態天候與日夜光影、雙聲道 3D 空間定位環境音、純程式生成貼圖 |
| **晨昏戰線 Duskline** | Deterministic Card Battle<br>`TypeScript` `WebRTC` `PeerJS` `Lockstep` | [⚔️ 線上對戰](https://wkai2573.github.io/duskline/) | 純函式規則引擎（不可變狀態與可重現 RNG）、WebRTC 免伺服器 P2P 開房對戰、Commit-Reveal 防偷看與鎖步校驗、貪婪 AI 模擬對弈 |
| **連擊大師 Combo Master** | 1v1 Web TCG<br>`React` `TypeScript` `PeerJS` `Cloudflare D1` | [🥊 線上遊玩](https://wkai2573.github.io/combo-master/) | 動態戰鬥流程圖系統即時追蹤位置、PeerJS 6 碼房號直接連線、Cloudflare Workers + D1 全球匿名戰績庫、機器人壓力測試 |

---

## ✨ 特色與互動設計

- **純粹極簡 Hero**：無多餘跳轉按鈕，視線自然流向精選作品。
- **點擊封面即玩**：點擊卡片封面圖直接彈出頁內燈箱（Iframe）暢玩，右上角可另開全螢幕。
- **分類即時篩選**：支援 3D 圖像渲染、策略卡牌、P2P 連線快速切換。
- **零依賴極速載入**：純原生 HTML5、CSS 與輕量 Canvas 星空互動。

---

## 🛠️ 本地預覽

```bash
# 使用 Python
python -m http.server 8000

# 或使用 Bun / Node
bunx serve .
# 或
npx serve .
```

---

© 2026 炸蝦 · Built with clean HTML & CSS.
