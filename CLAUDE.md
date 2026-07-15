# CLAUDE.md — authent-corp

This file provides guidance to Claude Code when working in this directory.

## プロジェクト概要

**株式会社オーセント コーポレートサイト**
- URL: https://authent-inc.com
- GitHub: `authent-tenshow/authent-corp`（main ブランチ）
- デプロイ: Vercel自動デプロイ（main push → 即反映）

## 構成

- `index.html` — メインページ（単一HTMLファイル構成）
- `hakaru_icon.svg` — HAKARUシンボルアイコン（白背景・角丸）

## デプロイフロー

```bash
git add <files>
git commit -m "変更内容"
git push origin main
# → Vercelが自動検知してauthent-inc.comに反映（1〜2分）
```

## 注意事項

- フレームワーク不使用・静的HTML
- フォント：Cormorant Garamond（serif）/ DM Mono（monospace）をGoogle Fontsから読み込み
- カラー：インディゴ背景 `#152542`、ゴールド `#d4a85a`
- 一時ファイル（picker系・logo_white/green系）はリポジトリに含めないこと
