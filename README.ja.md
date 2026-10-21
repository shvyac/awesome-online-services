# awesome-online-services（日本語）

[English README](README.md)

ブラウザ IDE、言語プレイグラウンド、コンバータ、正規表現、画像ツール、TTS など、開発者向けの便利なオンラインサービス集。

⭐ バッジは GitHub のスター数をリアルタイム表示します(shields.io)。

## 目次

- [ブラウザ IDE・サンドボックス](#ブラウザ-ideサンドボックス)
- [言語プレイグラウンド](#言語プレイグラウンド)
- [コンバータ・データツール](#コンバータデータツール)
- [正規表現](#正規表現)
- [数式・ダイアグラム](#数式ダイアグラム)
- [画像ツール](#画像ツール)
- [TTS／音声](#tts音声)
- [参考](#参考)
- [shvyac の awesome リスト](#shvyac-の-awesome-リスト)

---

## ブラウザ IDE・サンドボックス

### Replit
共同編集可能なブラウザベースの IDE で、現在は AI アプリビルダー（Replit Agent）としても展開。ローカル環境のセットアップなしで多くの言語を扱える。無料の Starter プランあり。

- https://replit.com/

### StackBlitz
ブラウザ上の即時フルスタック Web 環境（WebContainers）。フロントエンド／Node の試作に便利。同じチームが AI アプリビルダー Bolt.new も運営。

- https://stackblitz.com/
- https://bolt.new/

### CodeSandbox
ライブプレビュー、テンプレート、共同編集付きのオンラインコードサンドボックス — React や Web アプリに強い。現在は Together AI 傘下で、AI エージェント向けサンドボックスを動かす CodeSandbox SDK も提供。

- https://codesandbox.io/

### CodePen
HTML、CSS、JavaScript のフロントエンド向けプレイグラウンド。デモや UI 実験向き。CodePen 2.0 では複数ファイル対応の新エディタ、組み込みコンパイラ、デプロイ機能が追加された。

- https://codepen.io/

### JS Bin
ライブな HTML/CSS/JS 出力付きの共同 JavaScript デバッグ環境。オープンソースだがメンテナンスは最小限（最終コードプッシュは 2025 年半ば）で、ホスト版サイトは一時的につながらないことがある。

- https://jsbin.com/?html,output
- https://github.com/jsbin/jsbin ![GitHub stars](https://img.shields.io/github/stars/jsbin/jsbin?style=flat&label=%E2%AD%90)

## 言語プレイグラウンド

### SharpLab
.NET 言語プレイグラウンド — C# / IL / JIT / 逆コンパイルを並べて確認できる。

- https://sharplab.io/
- https://github.com/ashmind/SharpLab ![GitHub stars](https://img.shields.io/github/stars/ashmind/SharpLab?style=flat&label=%E2%AD%90)

### Rust Playground
公式の Rust プレイグラウンド — ブラウザで Rust をコンパイル・実行。

- https://play.rust-lang.org/
- https://github.com/rust-lang/rust-playground ![GitHub stars](https://img.shields.io/github/stars/rust-lang/rust-playground?style=flat&label=%E2%AD%90)

### Go Playground
公式の Go プレイグラウンド（正規 URL は現在 go.dev 上）。

- https://go.dev/play/

### TypeScript Playground
公式の TypeScript プレイグラウンド — 型、コンパイラオプション、出力 JS を探索できる。

- https://www.typescriptlang.org/play/

### Kotlin Playground
公式の Kotlin プレイグラウンド — Kotlin のスニペットをオンラインで試せる。

- https://play.kotlinlang.org/

### Compiler Explorer (Godbolt)
多数の言語・コンパイラにわたるコンパイラ出力（asm、IR、最適化）を探索できる。

- https://godbolt.org/
- https://github.com/compiler-explorer/compiler-explorer ![GitHub stars](https://img.shields.io/github/stars/compiler-explorer/compiler-explorer?style=flat&label=%E2%AD%90)

### 3v4l
オンライン PHP エディタ — 500 以上の PHP バージョンでコードを試せる。

- https://3v4l.org/

### Google Colab
Colaboratory — ブラウザ上の Python ノートブック（ML／データ作業に便利）。

- https://colab.research.google.com/

### JupyterLite
WebAssembly で動く、ブラウザ内で完結する Jupyter — サーバーもサインインも不要（Project Jupyter）。

- https://jupyter.org/try-jupyter/lab/
- https://github.com/jupyterlite/jupyterlite ![GitHub stars](https://img.shields.io/github/stars/jupyterlite/jupyterlite?style=flat&label=%E2%AD%90)

## コンバータ・データツール

### JSON to C#
Json2CSharp Toolkit — JSON サンプルから C# クラスをオンラインで生成（Java、Python、Dart にも対応）。

- https://json2csharp.com/

### quicktype
JSON から型とシリアライザを生成（TypeScript、Go、Rust、Python、C# など）。AI エージェント向けの MCP サーバーも提供。

- https://quicktype.io/
- https://github.com/glideapps/quicktype ![GitHub stars](https://img.shields.io/github/stars/glideapps/quicktype?style=flat&label=%E2%AD%90)

### transform.tools
コード変換ツール — JSON → TypeScript、SVG → JSX、CSS → Tailwind など。

- https://transform.tools/
- https://github.com/ritz078/transform ![GitHub stars](https://img.shields.io/github/stars/ritz078/transform?style=flat&label=%E2%AD%90)

### CyberChef
「サイバー・スイスアーミーナイフ」— エンコード／デコード、ハッシュ、圧縮、パース、操作の連鎖をクライアント側で実行。

- https://gchq.github.io/CyberChef/
- https://github.com/gchq/CyberChef ![GitHub stars](https://img.shields.io/github/stars/gchq/CyberChef?style=flat&label=%E2%AD%90)

### IT Tools
開発者向けの便利ツールを集めたオープンソースのコレクション（UUID／ハッシュ生成、各種変換、エンコーダ、ネットワーク計算など）。Docker でセルフホストも可能。

- https://it-tools.tech/
- https://github.com/CorentinTh/it-tools ![GitHub stars](https://img.shields.io/github/stars/CorentinTh/it-tools?style=flat&label=%E2%AD%90)

### jwt.io
JSON Web Token をデコードして検査（ヘッダ／ペイロード／署名）。Auth0（Okta）が運営。

- https://jwt.io/

### Hoppscotch
ブラウザ上のオープンソース API クライアント — REST、GraphQL、WebSocket など（Postman の代替）。

- https://hoppscotch.io/
- https://github.com/hoppscotch/hoppscotch ![GitHub stars](https://img.shields.io/github/stars/hoppscotch/hoppscotch?style=flat&label=%E2%AD%90)

### JSON Crack
JSON、YAML、XML、CSV をブラウザ上でインタラクティブなグラフとして可視化（オープンソース。有料機能は ToDiagram に移行）。

- https://jsoncrack.com/
- https://github.com/AykutSarac/jsoncrack.com ![GitHub stars](https://img.shields.io/github/stars/AykutSarac/jsoncrack.com?style=flat&label=%E2%AD%90)

### crontab.guru
cron のスケジュール式を手軽に編集し、意味を英語で解説してくれるエディタ（Cronitor 提供）。

- https://crontab.guru/

## 正規表現

### regex101
正規表現の作成、テスト、デバッグ。QUICK REFERENCE が便利。無料で使えるほか、Pro／Enterprise プランもある。

- https://regex101.com/

### RegExr
ライブハイライトとコミュニティパターン付きで RegEx を学び、作り、テストできる。

- https://regexr.com/
- https://github.com/gskinner/regexr ![GitHub stars](https://img.shields.io/github/stars/gskinner/regexr?style=flat&label=%E2%AD%90)

## 数式・ダイアグラム

### HostMath
オンライン LaTeX 数式エディタ／ブラウザベースの数式エディタ（利用可能だが更新は止まっている）。

- https://www.hostmath.com/
- https://www.hostmath.com/Demo

### Mermaid Live Editor
Mermaid ダイアグラム（フローチャート、シーケンス、ER など）をブラウザで編集・プレビュー。

- https://mermaid.live/
- https://github.com/mermaid-js/mermaid-live-editor ![GitHub stars](https://img.shields.io/github/stars/mermaid-js/mermaid-live-editor?style=flat&label=%E2%AD%90)

### Excalidraw
手書き風のホワイトボード。ダイアグラムやスケッチ用で、共有リンクあり。

- https://excalidraw.com/
- https://github.com/excalidraw/excalidraw ![GitHub stars](https://img.shields.io/github/stars/excalidraw/excalidraw?style=flat&label=%E2%AD%90)

### draw.io (diagrams.net)
無料のダイアグラムエディタ — フローチャート、UML、ER、ネットワーク図、BPMN など。Visio（.vsdx）、Gliffy、Lucidchart のファイルも読み込める。

- https://app.diagrams.net/
- https://github.com/jgraph/drawio ![GitHub stars](https://img.shields.io/github/stars/jgraph/drawio?style=flat&label=%E2%AD%90)

### tldraw
スケッチやダイアグラム向けの無限キャンバス型ホワイトボード。キャンバスアプリを作るための SDK としても提供。

- https://www.tldraw.com/
- https://github.com/tldraw/tldraw ![GitHub stars](https://img.shields.io/github/stars/tldraw/tldraw?style=flat&label=%E2%AD%90)

### Typst
マークアップベースのモダンな組版システム（LaTeX の代替）。typst.app で共同編集できる Web エディタを提供し、数式の多い文書に便利。

- https://typst.app/
- https://github.com/typst/typst ![GitHub stars](https://img.shields.io/github/stars/typst/typst?style=flat&label=%E2%AD%90)

### Carbon
ドキュメントや SNS 向けに、ソースコードのきれいなスクリーンショットを作成。

- https://carbon.now.sh/
- https://github.com/carbon-app/carbon ![GitHub stars](https://img.shields.io/github/stars/carbon-app/carbon?style=flat&label=%E2%AD%90)

### ray.so
Raycast 製のコードスクリーンショット生成ツール — テーマや背景を選び、PNG／SVG で書き出し。

- https://ray.so/
- https://github.com/raycast/ray-so ![GitHub stars](https://img.shields.io/github/stars/raycast/ray-so?style=flat&label=%E2%AD%90)

## 画像ツール

### Squoosh
画像圧縮 Web アプリ — ブラウザ内でローカルにリサイズ／エンコード（プライバシーに配慮）。

- https://squoosh.app/
- https://github.com/GoogleChromeLabs/squoosh ![GitHub stars](https://img.shields.io/github/stars/GoogleChromeLabs/squoosh?style=flat&label=%E2%AD%90)

### SVGOMG
SVGO の Web GUI — ブラウザ上で SVG ファイルを最小化・整理。

- https://jakearchibald.github.io/svgomg/
- https://github.com/jakearchibald/svgomg ![GitHub stars](https://img.shields.io/github/stars/jakearchibald/svgomg?style=flat&label=%E2%AD%90)

### Photopea
ブラウザで動く高機能オンライン写真エディタ（PSD 対応）。

- https://www.photopea.com/

## TTS／音声

### 音読さん
日本語 音声読み上げソフト — テキストを読み上げ、MP3 としてダウンロード可能。新しい AI 音声をベータ提供中（従来版も引き続き利用可）。

- https://ondoku3.com/ja/

## 参考

関連する awesome リスト:

- https://github.com/styfle/awesome-online-ide ![GitHub stars](https://img.shields.io/github/stars/styfle/awesome-online-ide?style=flat&label=%E2%AD%90)
- https://github.com/hql287/awesome-free-services ![GitHub stars](https://img.shields.io/github/stars/hql287/awesome-free-services?style=flat&label=%E2%AD%90)

## shvyac の awesome リスト

[shvyac](https://github.com/shvyac) が管理しているキュレーションリストの一覧:

- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
