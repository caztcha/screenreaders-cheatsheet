# スクリーンリーダー基本操作チートシート


ウェブサイトやアプリケーションのアクセシビリティ検証では、各種スクリーンリーダーを実際に用いてインタラクションを確認する作業が不可欠です。その際、スクリーンリーダーの操作方法を確認したくなることがしばしばあると思います。

このチートシートは、ウェブアクセシビリティの検証作業時によく行なうスクリーンリーダーの基本操作を、一枚のスプレッドシートにまとめたものです。Google スプレッドシートで公開しています。

- [スクリーンリーダー基本操作チートシート (Google スプレッドシート)](https://docs.google.com/spreadsheets/d/1_F6L_VC2v-ZJKSbjqtk0EFW1zoBu5pgFcAGLtu6kVwQ/edit?usp=sharing)

各種スクリーンリーダーの操作方法を、(それぞれの公式ドキュメントで調べる手間をかける代わりに) 手元で簡単に確認できるリファレンスとして活用いただくことを意図しています。ウェブアクセシビリティ検証の観点で「これだけは押さえておきたい」操作をリストアップして、主要なスクリーンリーダーの操作方法を一覧できるようにまとめているので、ウェブアクセシビリティの初学者向けの教材としても参考になれば幸いです。

## チートシートの概要

このチートシートで取り上げているスクリーンリーダーは以下のとおりです。

- NVDA (Windows)
- ナレーター (Windows)
- PC-Talker Neo (Windows)
- VoiceOver (macOS)
- VoiceOver (iOS)
- TalkBack (Android)

これらのスクリーンリーダーそれぞれについて、以下の基本操作をまとめています。

- 読み上げの停止
- 前後のセクションの読み上げ
- フォーカス可能なオブジェクトへの移動
- 見出しの拾い読み
- ランドマーク間の移動
- フォームへの移動
- リストへの移動
- リスト内の各項目への移動
- リンクへの移動
- ボタンへの移動
- テーブルへの移動
- テーブル内の読み上げ対象セルの移動 (上下左右)
- 画像に移動
- モード (ブラウズ / 文字入力) の切り替え
- 画面スクロールのジェスチャ

## このチートシートの編集方針

このチートシートをまとめるにあたっては、以下を編集方針としています。

### セルに「あれこれ」書きすぎない

スプレッドシートの見やすさを重視し、セルの中に「あれこれ」書きすぎないようにしています。

たとえば、VoiceOver (macOS) では「見出しの拾い読み」が「[control] ＋ [option] ＋ [command] ＋ [H] キー」でも「Web ローター」でも可能なのですが、敢えて後者のみを記述しています。これは恣意的ですが、macOS VoiceOver では他の操作 (ランドマーク間の移動、フォームやテーブルへの移動、など) でも「Web ローター」を用いることが多いので、それらに合わせたほうが使いやすいだろうと判断しています。

### スクリーンリーダー固有の装飾キーや機能呼び出しジェスチャを記憶していなくても使えるようにする

Windows および macOS のスクリーンリーダーには、固有の装飾キーを持つものがあります。

- NVDA (Windows) : 「NVDA キー」
- ナレーター (Windows) : 「ナレーターキー」
- VoiceOver (macOS) : 「VO キー」

このチートシートでは、これらの装飾キーを記憶していなくても使えるように、デフォルトのキー構成を用いる前提で、具体的なキー名を書き出しています。(「NVDA キー」および「ナレーターキー」は [insert] キー、「VO キー」は [control] ＋ [option] キー、という具合です。)

また、VoiceOver (macOS) には「Web ローター」、VoiceOver (iOS) には「ローター」、TalkBack (Android) には「読み上げコントロール」という固有の機能呼び出しジェスチャが用意されています。これらのジェスチャも記憶することなく使えるように、チートシートの脚注に説明を記述しています。

### Windows のスクリーンリーダーを Mac で操作することも想定する

Windows のスクリーンリーダーを、macOS (Parallels Desktop) で操作することもあるかと思います。その場合、Windows マシン特有の装飾キーは使えないため、Mac で使用可能な装飾キーも併記しています。たとえば、Windows の [insert] キーに相当する Mac での操作は、[fn] ＋ [return] キーになります。また、Windows の [alt] キーに相当する Mac での操作は、[option] キーになります。

---

このチートシートは、ご自身の Google ドライブにコピーしたり、あるいは Excel ファイルとしてダウンロードしてお使いいただくことができます。スクリーンリーダー固有の装飾キーやジェスチャをカスタマイズしている方もいるかと思いますが、お手元で適宜編集して、ご活用いただければ幸いです。
