# TWM Fleet｜台灣大艦隊 7 年航程

互動品牌網站（純靜態，不需要建置）。

- `index.html`：網站本體（3D 模型、貼圖、字型都已內嵌）
- `bgm.mp3`：背景音樂

每個檔案都小於 25 MiB（Cloudflare Pages 單檔上限）。

## 部署

推送到 `main` 分支後自動部署：
- Netlify：Build command 留空，Publish directory 為 `.`（見 `netlify.toml`）
- Cloudflare Pages：Framework preset 選 None，Build command 留空，Build output directory 填 `/`

## 版本

目前版本：index62（2026/11/6）
