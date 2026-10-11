# wkai · 專案作品集

> Creative Developer & Game Craftsman
> 專注於 Three.js / WebGL 程序化圖像渲染、自製純函式卡牌遊戲引擎 與 WebRTC P2P 即時對戰。

🌐 **線上訪問**：[https://wkai2573.github.io/](https://wkai2573.github.io/)

---

## 🎮 精選專案列表

| 專案名稱 | 類型與技術棧 | 線上體驗 | 開源倉庫 | 核心技術亮點 |
| :--- | :--- | :--- | :--- | :--- |
| **守燈人 · The Lamplighter** | 2.5D Atmospheric Adventure<br>`Three.js` `WebGL` `Web Audio` `Bun` | [🎮 開啟遊玩](https://wkai2573.github.io/lamplighter/) | [GitHub ↗](https://github.com/wkai2573/lamplighter) | 窄視角透視真實 3D 視差、解析積分自製霧氣體積散射、Karplus-Strong 撥弦生成式配樂、約 780 KB 極速啟動 |
| **雨夜便利商店與秋夜旅館** | WebGL Miniature Scenes<br>`Three.js` `GLSL` `SSAO` `Spatial Audio` | [👀 進入場景](https://wkai2573.github.io/3d-miniature-scenes/) | [GitHub ↗](https://github.com/wkai2573/3d-miniature-scenes) | 三渲二（Toon Shader＋描邊）與 SSAO 環境光遮蔽、動態天候與日夜光影、雙聲道 3D 空間定位環境音、純程式生成貼圖 |
| **晨昏戰線 Duskline** | Deterministic Card Battle<br>`TypeScript` `WebRTC` `PeerJS` `Lockstep` | [⚔️ 線上對戰](https://wkai2573.github.io/duskline/) | [GitHub ↗](https://github.com/wkai2573/duskline) | 純函式規則引擎（不可變狀態與可重現 RNG）、WebRTC 免伺服器 P2P 開房對戰、Commit-Reveal 防偷看與鎖步校驗、貪婪 AI 模擬對弈 |
| **連擊大師 Combo Master** | 1v1 Web TCG<br>`React` `TypeScript` `PeerJS` `Cloudflare D1` | [🥊 線上遊玩](https://wkai2573.github.io/combo-master/) | [GitHub ↗](https://github.com/wkai2573/combo-master) | 動態戰鬥流程圖系統即時追蹤位置、PeerJS 6 碼房號直接連線、Cloudflare Workers + D1 全球匿名戰績庫、機器人壓力測試 |

---

## 🔬 Engineering Focus · 技術光譜

- **程序化渲染與圖像**：Three.js, WebGL, 自製 Toon Shader、體積光霧散射、SSAO、動態陰影與粒子系統。
- **純函式規則引擎**：不可變狀態轉換（Immutable State）、可重現亂數產生器（RNG Seed）、事件驅動渲染、千局 AI 自我對弈平衡模擬。
- **P2P 連線與邊緣運算**：WebRTC / PeerJS 無伺服器雙人連線、Lockstep 鎖步協定、Commit-Reveal 雜湊防作弊、Cloudflare Workers + D1 邊緣資料庫。
- **即時音訊合成**：Web Audio API 純程式合成環境音、Karplus-Strong 撥弦演算法生成式配樂、3D 空間定位音場。

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

© 2026 [wkai](https://github.com/wkai2573) · Built with clean HTML & CSS.
