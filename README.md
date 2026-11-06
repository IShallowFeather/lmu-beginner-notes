# LMU 新手練習筆記

給剛開始跑模擬賽車的玩家看的繁體中文練習網站。每篇文章聚焦一個可以重複練習的技巧，說明練什麼、看什麼，以及怎麼調整。

## 專案規則

開始新增或修改頁面前，先讀 [`AGENTS.md`](./AGENTS.md)。裡面有目錄結構、文章格式、網站風格、無障礙要求與完成前檢查清單。

## 頁面

- [練習首頁](./index.html)
- [穩定煞車與煞車點](./pages/braking-basics.html)
- [循跡與彎道出彎](./pages/corner-exit.html)

## 線上版本

- Repository：<https://github.com/IShallowFeather/lmu-beginner-notes>
- GitHub Pages：<https://ishallowfeather.github.io/lmu-beginner-notes/>

## 本機預覽

在專案根目錄執行：

```bash
python3 -m http.server 8000
```

再用瀏覽器開啟 `http://localhost:8000/`。這個專案不需要安裝套件或建置。

## GitHub Pages

網站目前由 GitHub Pages 從 `main` 分支根目錄發布；推送到 `main` 後會更新線上版本。首頁為 `index.html`。新增頁面要照 `AGENTS.md` 的規則加入首頁索引。

## 後續擴充

可以新增輪胎暖胎、視線選擇、車內設定等主題。先按文章範本完成單頁，再把入口加到首頁；不要把所有文章塞進同一個 HTML 檔。
