# 📄 Marp CLI によるスライド変換手順書

## 🛠️ 前提条件
- Node.js がインストールされていること
- Marp CLI のインストール（初回のみ）

```bash
npm install -g @marp-team/marp-cli
```

## 📁 ファイル構成（例）

```
/slides
├── kaeru_slide_template.md
```

## 📤 PDFに変換する場合

```bash
marp kaeru_slide_template.md --pdf
```

## 📤 PowerPoint (PPTX) に変換する場合

```bash
marp kaeru_slide_template.md --pptx
```

## 🎨 テーマをカスタムしたい場合（例：themes/custom.css）

```bash
marp kaeru_slide_template.md --pdf --theme themes/custom.css
```
