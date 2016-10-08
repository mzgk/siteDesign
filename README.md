# mzgkworks.com デザイン プロジェクト
## 目的
- mzgkworks.com（Hugo + GitHubPages）のデザインを構築する
- ２カラム・ヘッダー背景は画面幅
- 組み上がったらhugoのテーマに変換する


## 対象
- [ ] トップ画面
	- [x] ヘッダ
	- [ ] 右カラム
	- [ ] 左カラム
	- [ ] フッター
- [ ] 記事画面
- [ ] About画面
- [ ] プロダクト画面


## 方針
- htmlで画面レイアウト作成
- scssでスタイルを作成
- `$sass --watch --style expanded scss:css` でcssにコンパイル
- 最終的には
  - HTML : Hugoのテンプレートに変換
  - CSS  : `--style compress` で圧縮形式
  - Hugo : テーマディレクトリにscssを追加する
- CSS設計手法は、なるべくBEMに沿った手法にする
- Webフォント・FontAwesomeを使用
- 「現場のプロが本気で教える HTML/CSSデザイン講義」を参考にする
