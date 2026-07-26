# 青葉のカメラ

　「青葉のカメラ」は、艦隊これくしょん～艦これ～ でゲーム画面のスクリーンショットを簡単に取得するためのChrome拡張です。Chromeの機能のみで実装されていますので、macOSでも利用可能です。  
　スクリーンショット取得のためメニューや撮影フレームの表示のため画面に独自のタグを追加しますが、ゲームや通信データへの介入、サーバへの直接アクセス等の処理は一切行っていません。  

# Flight-IIA mode対応について
オリジナル作者のKomit様作成のリポジトリをフォークし、Flight-IIA mode（セキュア化https移行）への対応を行いました。使い方、ライセンスはフォーク前と同じです。

#### YouTube
[<img src="http://img.youtube.com/vi/pfFuOBjqqKM/0.jpg" alt="「青葉のカメラ」の使い方" title="「青葉のカメラ」の使い方" width="480px" />](https://www.youtube.com/watch?v=pfFuOBjqqKM)

## インストール
GitHubからzipファイルをダウンロード、zipファイルを展開し、Chromeのデベロッパーモードを有効にして読み込んでください。  
具体的な手順は"GitHubで公開されているChrome拡張機能をインストールする方法"等でWeb検索した結果を参考にしてください。

現在、Flight-IIA mode対応版はChromeウェブストアの登録がリジェクトされていますので、Chromeウェブストアからのインストールはできません。  
Chromeウェブストアに登録されているのはFlight-IIA modeに対応していないオリジナル版です。

## 注意事項・制限
  - **本拡張はインストール/アップデート時に艦これのゲーム画面が開いている場合は、ゲーム画面をリロードするまで動作しません。**
  - キャプチャ時には若干のタイムラグが発生します。よって戦闘中の一瞬の瞬間を狙うのには向いていません。
  - ホットキーはゲーム画面がアクティブでない場合は動作しません。

## ライセンス
オリジナルの著作権者：Komit様 [MITライセンス](https://github.com/Komit/AobaNoCamera/blob/master/LICENSE.md)

フォーク後の当リポジトリのライセンスも[MITライセンス](https://github.com/sagann123/AobaNoCamera/blob/master/LICENSE.md)です。

以下のライブラリ・素材については各オリジナルのライセンス・ガイドラインに従います。
- [jQuery](http://jquery.com/) ([ライセンス](https://jquery.org/license/))
- [FileSaver.js](https://github.com/eligrey/FileSaver.js) ([ライセンス](https://github.com/eligrey/FileSaver.js/blob/master/LICENSE.md))
- [JavaScript Canvas to Blob](https://github.com/blueimp/JavaScript-Canvas-to-Blob) ([ライセンス](https://github.com/blueimp/JavaScript-Canvas-to-Blob))
- シャッター音 [サウンドオフィスドットコム](http://www.soundoffice.com/se/item/se-033.php) ([ガイドライン](http://www.soundoffice.com/se/guideline.php))
