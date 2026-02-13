[English](README.md) | [繁體中文](README.zh.md)

# canvas-design

一個 Claude Code 技能，透過設計哲學創造精美的 .png 和 .pdf 視覺藝術作品。先產生設計哲學宣言，再將其以專家級工藝水準視覺化呈現於畫布上。

## 說明

1. 創建 **設計哲學** -- 一個具名的美學運動，包含形式、空間、色彩與構圖的具體原則
2. 從使用者的需求中推導 **微妙引用**，將其無形地織入作品中
3. 產出 **畫布** -- 博物館等級的 .pdf 或 .png 藝術品，以精雕細琢的工藝體現哲學
4. 進行 **精煉修整**，將每個細節打磨至完美品質

## 功能特色

- 產生原創設計哲學作為具名藝術運動
- 產出高品質的 .png 和 .pdf 視覺輸出
- 包含精選字型庫（`canvas-fonts/`），提供 30 種以上字體及 OFL 授權
- 強調視覺表達而非文字 -- 設計 90% 為視覺、10% 為必要文字
- 支援多頁輸出，可製作咖啡桌書風格的作品集

## 前置條件

- **Playwright MCP** -- 作為渲染引擎。技能會撰寫 HTML/CSS，透過 Playwright 瀏覽器開啟並截圖為 PNG。PDF 輸出使用 `write_pdf` 工具。
- **CJK 字型**（中文文字用）-- macOS 可使用內建的 `PingFang TC`，或安裝 `Noto Sans CJK TC`。
- 不需要外部 API 金鑰

## 安裝

```bash
git clone https://github.com/joneshong-skills/canvas-design.git ~/.claude/skills/canvas-design
```

## 使用方式

```
/canvas-design 建立一張日式極簡風格的海報
/canvas-design 設計一幅關於時間流逝的視覺作品
/canvas-design 製作捕捉雨天午後感覺的藝術品
```
