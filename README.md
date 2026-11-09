<div align="center">

# こんにちは！kume です 👋

**金沢工業大学 情報工学科**　|　ものづくりが好きなエンジニア志望

[![Portfolio](https://img.shields.io/badge/Portfolio-soki0909.github.io-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://soki0909.github.io/)
[![GitHub followers](https://img.shields.io/github/followers/Soki0909?style=for-the-badge&logo=github&label=フォロワー)](https://github.com/Soki0909)

</div>

---

## 🙋 About

金沢工業大学 情報工学科。Web・モバイル・デスクトップ・CLI と幅広く開発。  

**Languages:**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,ts,kotlin,js,java,c,rust,dart,cs,cpp,swift" />
  </a>
</p>

生成AI・AIエージェントを活用した設計・実装・検証にも取り組んでいます。

**Tools:**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nodejs,androidstudio,git,react,flutter,fastapi,firebase,opencv,tauri,dotnet" />
  </a>
</p>

![Chrome Extension](https://img.shields.io/badge/Chrome_Extension-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)

**Communication / Protocols:**

複数プロジェクトで端末間通信の設計・実装を繰り返し担当してきた結果、以下のプロトコル・通信方式に理解がある。

![BLE](https://img.shields.io/badge/BLE-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![UDP](https://img.shields.io/badge/UDP-4F46E5?style=for-the-badge&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Firebase Realtime](https://img.shields.io/badge/Firebase%20Realtime-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![ESP-12E](https://img.shields.io/badge/ESP--12E-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white)

---

## 🚀 制作物

> 📝 **掲載リポジトリのドキュメント（README・技術仕様書）はすべて私が執筆しています。**

---

## 🏆 ハッカソン

#### [4DX@HOME](https://github.com/jphacks/kz_2504) — JPHacks 2025

[![JPHacks Best Hackday Award](https://img.shields.io/badge/JPHacks%202025-🥇%20Best%20Hackday%20Award-gold?style=flat-square)](https://jphacks.com/information/hackday-result-2025/)
[![Award Day Finalist](https://img.shields.io/badge/JPHacks%202025-🎯%20Award%20Day%20Finalist-blue?style=flat-square)](https://jphacks.com/information/award-finalists2025/)
[![審査委員特別賞](https://img.shields.io/badge/JPHacks%202025-🏅%20審査委員特別賞-silver?style=flat-square)](https://jphacks.com/2025/result/innovator/)
[![Innovator認定](https://img.shields.io/badge/JPHacks%202025-💡%20Innovator認定-purple?style=flat-square)](https://jphacks.com/2025/result/innovator/)
[![企業賞3社](https://img.shields.io/badge/企業賞-3社受賞-orange?style=flat-square)]()

**AI動画解析による家庭用4DXシステム。** 任意のMP4動画をGemini 2.5 Pro Visionで解析し、振動・光・風・水・色の5種類の物理フィードバックを自動生成。  
Webアプリ（React + TypeScript） × Cloud Run API（FastAPI） × Raspberry Pi Hub × ESP-12E × 4台の3層アーキテクチャ。  
映像と物理効果の同期誤差は **±100ms以内**。3Dプリント筐体も自作。  
担当：**APIサーバー構築 / WebアプリとRaspberry Pi双方の通信制御・実装**。

> 🔗 [Live Demo](https://kz-2504.onrender.com)

> ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white) ![ESP-12E](https://img.shields.io/badge/ESP--12E-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

> 📝 **README・技術仕様書（5種）を執筆**

---

#### [Screact](https://github.com/KIT-DevelopersHub/screact) — THE HACK 2026

[![THE HACK 2026 大賞](https://img.shields.io/badge/THE%20HACK%202026-🏆%20大賞-gold?style=flat-square)](https://github.com/KIT-DevelopersHub/screact)

**既存のモニターやプロジェクターを、指で描いて操作できる画面へ。** Androidスマホで手指を認識し、PC上の画面へ描画・クリック・スクロールなどの操作を反映。  
MediaPipeによる手指認識、ArUcoとHomographyによる画面座標変換、One-Euro Filterによる平滑化を組み合わせ、UDP自動発見とWebSocketでスマホとPCを接続。  
**THE HACK 2026 本戦で大賞を受賞**。

> 🔗 [デモ動画（約33秒）](https://drive.google.com/file/d/14SZvVKVLxcpKkB3tEl41TTzPK-4H_XEj/view?usp=sharing)

> ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-00A67E?style=for-the-badge) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

> 📝 **README・Android / Desktop / 通信仕様書を執筆**

---

#### [Re:Cooplay](https://github.com/jphacks/kz_2613) — JPHACKS 2026

[![Hack Day Audience Award](https://img.shields.io/badge/JPHACKS%202026-🏆%20Hack%20Day%20Audience%20Award-gold?style=flat-square)](https://github.com/jphacks/kz_2613)

**1人用のPCゲームに、複数人の協力プレイを後付けするシステム。** 1つのキャラクターの移動・視点・攻撃などを2〜4人で役割分担し、ゲーム本体を改造せずに共同操作。  
スマホのブラウザから参加し、ゲームや人数に応じて操作を割り当て。Rust製PCホストで入力を統合し、WebRTC DataChannel・WebSocketとWindows APIを活用。  
**JPHACKS 2026 金沢会場 Hack Day Audience Awardを受賞**。

> 🔗 [紹介動画](https://youtu.be/a8uhU2ymsuQ)

> ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white) ![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=for-the-badge&logo=tauri&logoColor=white) ![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socketdotio&logoColor=white) ![Windows](https://img.shields.io/badge/Windows%20API-0078D4?style=for-the-badge&logo=windows&logoColor=white)

> 📝 **README・総合仕様書・通信仕様書を執筆**

---

#### [omoi](https://github.com/Ruaku1352/omoi) — Tornado 2026

[![NTTレゾナントテクノロジー賞](https://img.shields.io/badge/Tornado%202026-🏆%20NTTレゾナントテクノロジー賞-gold?style=flat-square)](https://github.com/Ruaku1352/omoi)

**一枚の写真ではなく、一つの思い出を飾る。** 複数の写真と思い出テキストから、AIが人物・場所・物などの要素を選び、多層の立体レイヤーアートへ再構成。  
React製Webアプリで3Dプレビューと2D編集を行い、FastAPI・Gemini・画像処理で作品データを生成。実際に飾れる物理作品への出力にも対応。  
**Tornado 2026でNTTレゾナントテクノロジー賞を受賞**。

> 🔗 [Live Demo](https://omoi-506412.web.app/)

> ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

> 📝 **README・システム仕様書・ギャラリーを執筆**

---

#### [EnCounter](https://github.com/razy6174/EnCounter) — スマプロハッカソン 2026

[![スマプロ最優秀賞](https://img.shields.io/badge/スマプロハッカソン%202026-🏆%20最優秀賞-gold?style=flat-square)](https://www.smartphone-programming.com/)

**ハイパーローカル・すれちがいマッチングアプリ。** BLE（Bluetooth Low Energy）で半径数メートル以内の「すれ違い」をリアルタイム検知し、気分(Mood)と興味タグが一致した時だけマッチング通知。  
位置情報不要・匿名認証・ステルスモード搭載。チャット、すれちがい図鑑、鼓動風バイブレーション通知を実装。  
担当：**バックエンド / アーキテクチャ設計 / BLE通信 / Firebase連携**。

> ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black) ![Android BLE](https://img.shields.io/badge/Android%20BLE-3DDC84?style=for-the-badge&logo=android&logoColor=white) ![Hilt](https://img.shields.io/badge/Hilt-34A853?style=for-the-badge&logo=google&logoColor=white) ![Coroutines/Flow](https://img.shields.io/badge/Coroutines%20%2F%20Flow-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

> 📝 **README・バックエンド仕様書・フロントエンド仕様書を執筆**

---

#### [Sleep Buster](https://github.com/Saisei2004/WILDCARD) — Hackit 2025

[![Hackit 最優秀賞](https://img.shields.io/badge/Hackit%202025-🏆%20最優秀賞-gold?style=flat-square)](https://hackit-website.vercel.app/)

**みんなの朝を「つなぐ」アラームアプリ。** 友達が遠隔操作でロボット「バスタ君」（LEGO EV3製）を動かし、寝坊した人を**物理的に**たたき起こす。  
SkyWay WebRTCによるリアルタイム映像確認、Firebase経由の起床ステータス同期、Bluetooth制御を実装。  
8チームが参加する学内ハッカソン「Hackit 2025」で **最優秀賞を受賞**。  
担当：**SkyWay WebRTCによるリアルタイム映像確認の実装**。

> ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black) ![SkyWay WebRTC](https://img.shields.io/badge/SkyWay%20WebRTC-0078D4?style=for-the-badge&logo=webrtc&logoColor=white) ![LEGO EV3](https://img.shields.io/badge/LEGO%20EV3-E3000B?style=for-the-badge&logo=lego&logoColor=white)

> 📝 **README・システム仕様書（全15章）を執筆**

---

### 🌐 個人開発 & Chrome 拡張

| プロジェクト | 概要 | 技術 |
|---|---|---|
| [**Shortcut Manager**](https://github.com/Soki0909/windows-shortcut-manager) | Windowsのショートカットキーにアプリ・Webサイト・Chromeタブグループなどを割り当てる管理ツール（正式版準備中） | ![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| [**ポートフォリオサイト**](https://github.com/Soki0909/Soki0909.github.io) | 自作ポートフォリオサイト ([公開中](https://soki0909.github.io/)) | ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) |
| [**happy-chicken-ticket-system**](https://github.com/Soki0909/happy-chicken-ticket-system) | 工大祭屋台で使用したQRコードベースのリアルタイム整理番号管理システム | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| [**pdf_to_markdown**](https://github.com/Soki0909/pdf_to_markdown) | PDFをMarkdown形式に変換するCLIツール | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| [**KyoinAssist**](https://github.com/Soki0909/KyoinAssist) | 出欠や生徒情報の管理を支援するAndroidアプリ（授業制作） | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) |
| [**sum-equals-concat**](https://github.com/Soki0909/sum-equals-concat) | 数列の和が両端の整数を連結した数に等しくなる組を探索するプログラム | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| [**PianoApp**](https://github.com/Soki0909/PianoApp) | OpenGLで制作した3D電子ピアノ | ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) |
| [**subject_semester_sorter**](https://github.com/Soki0909/subject_semester_sorter) | KITナビ上で年度・学期の履修科目を一覧表示（Chrome拡張） | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| [**kit_navi_autofocus**](https://github.com/Soki0909/kit_navi_autofocus) | 大学ポータルのログイン・ナビ操作を自動化（Chrome拡張） | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| [**think_before_ai**](https://github.com/Soki0909/think_before_ai) | 生成AIサイトを開く前に「本当に必要？」と問いかけるポップアップ（Chrome拡張） | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| [**Quick Tab Mover**](https://github.com/Soki0909/quick-tab-mover) | キーボード操作でChromeのタブを別ウィンドウへ移動・タブ間ジャンプ（Chrome拡張） | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| [**Shortcut New Tab**](https://github.com/Soki0909/shortcut-newtab) | 新規タブをキーボード中心のランチャーへ置き換えるChrome拡張 | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| [**Focus Escape**](https://github.com/Soki0909/focus-escape) | Webページ上のフォーカスをショートカットキーで解除するChrome拡張 | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |

---

## 📊 GitHub 統計

<div align="center">

<img height="170" src="./profile/stats.svg" />
<img height="170" src="./profile/langs.svg" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Soki0909&theme=tokyonight&locale=ja&hide_border=true&date_format=%5BY.%5Dn.j)](https://git.io/streak-stats)

</div>

---

<div align="center">

**訪問ありがとうございます！** 気になるリポジトリがあれば ⭐ をもらえると嬉しいです 😊

![Profile Views](https://komarev.com/ghpvc/?username=Soki0909&color=blueviolet&style=flat-square&label=Profile+Views)

</div>
