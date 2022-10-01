Title: Getting started with KAGEX

Date: 2012/4/29

Author: Watanabe Go.

1. ベースの取得

　Subversion を使って吉里吉里公式レポジトリから以下を取得します。

　  https://sv.kikyou.info/svn/kirikiri2/tags/kag3ex3

2. 実行ファイルを展開

  レポジトリから吉里吉里のバイナリ配布をダウンロードして配置します
  https://sv.kikyou.info/svn/kirikiri2/trunk/kirikiri2/bin/win32

  ※開発版バイナリ最新(Rev.5034)以降でしか動作確認されていません

 krkr.exe を実行するとサンプルのシステムが起動します。

3. サンプルデータについて

  template/   ベースになるテンプレートファイルです
  data/       システムスクリプト（タイトル画面他）まで含んだサンプルです。

  data/ 以下のファイルは template/system を参照しています。

  実際のゲームのリリース時には template/system と template/startup.tjs 
　を data 以下にそのままコピーしたほうが良いでしょう
