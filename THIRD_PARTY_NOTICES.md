# 第三者ソフトウェア

アプリ本体は `LICENSE.txt` に定める無償プロプライエタリソフトウェアです。
以下の第三者の構成要素にはアプリ本体の利用条件ではなく、それぞれの権利者が定める
ライセンスが適用されます。

ウマ娘因子比較アプリ　サポカ外因子チェッカーは、PaddlePaddle、PaddleOCR、PaddleX、FastAPI、Uvicorn、
NumPy、Pillowなどの第三者ソフトウェアを利用します。

PaddleXが任意で利用する `ujson` は不要なネイティブ拡張のため配布物から除外し、
Python標準の `json` 実装へフォールバックします。

Windows配布物には、OCRのネイティブ依存を満たすため、未改変のMicrosoft署名済み
Visual C++ Runtime DLL（x64）をアプリローカルに同梱します。対象ファイルとSHA-256は
`licenses/Microsoft-Visual-Cpp-Runtime/NOTICE.txt` に記録し、再頒布は適用される
Microsoft Visual Studioライセンス条項に従います。

Windows配布物の `THIRD_PARTY_PACKAGES.md` には、実際に同梱したパッケージの
名称、バージョン、ライセンスメタデータを記録します。取得できたライセンス本文は
配布物の `licenses/` に収録します。

OCR認識モデルは `PP-OCRv5_server_rec` を同梱します。モデルの名称と構成ファイルは
`release-manifest.json` に記録し、アプリ実行時には配布物内のモデルだけを使用します。
モデルカードはApache License 2.0を指定しており、ライセンス本文を
`licenses/PP-OCRv5_server_rec/LICENSE` に収録します。
