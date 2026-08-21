# サポカ外因子チェッカー　ウマ娘因子比較アプリ v0.1.8

ウマ娘の因子画像をOCRで読み取り、因子を比較するWindows向けローカルアプリです。

本アプリは無料非公式ツールです。ゲーム本体、Cygames、その他の権利者とは関係ありません。

## ダウンロード

[GitHub Releases](https://github.com/abu732/uma-musume-factor-comparison-app/releases/latest)から、次のファイルをダウンロードしてください。

- `UmaFactor-win-x64-portable-v0.1.8.zip`

同じReleaseにある`SHA256SUMS.txt`で、ダウンロードしたZIPのSHA-256を確認できます。

## 使い方

1. ZIPを右クリックし、Windows標準の「すべて展開」を選びます。
2. 展開先の`Uma`フォルダを開きます。
3. `アプリを起動.cmd`をダブルクリックします。
4. ブラウザで画像を選び、OCRを実行します。
5. 終了時は画面の終了操作、または`アプリを終了.cmd`を使用します。

インストール、管理者権限、PythonやOCRエンジンの別途導入は不要です。OCRは同梱モデルを使ってPC内で実行され、選択した画像やOCR結果を外部サービスへ送信しません。

詳しい手順と注意事項は、Releaseに添付した`README-FIRST.txt`と`PORTABLE-GUIDE.txt`を確認してください。

## 対応環境と警告

- Windows 10／11（64bit）
- 画面表示にはMicrosoft Edgeなどのブラウザを使用
- インターネット接続なしでOCR可能

本アプリにはコード署名がありません。ダウンロード時や初回起動時に、Microsoft Defender SmartScreenなどの警告が表示される場合があります。セキュリティ機能を無効化せず、配布元とSHA-256を確認したうえで判断してください。

アプリ本体の終了後もブラウザタブが残る場合があります。その場合、ブラウザの閉じるボタンでタブを閉じて問題ありません。作業データを削除する場合は`作業データを削除.cmd`を実行し、不要になった展開フォルダを削除してください。

## ライセンスと利用条件

本アプリは、無料プロプライエタリです。利用・再配布などの条件は[LICENSE.txt](LICENSE.txt)を確認してください。

第三者ソフトウェアのライセンスは[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)に記載しています。

「ウマ娘 プリティーダービー」に関する権利は各権利者に帰属します。利用にあたっては、[「ウマ娘 プリティーダービー」二次創作ガイドライン](https://umamusume.jp/derivativework_guidelines/)も確認してください。
