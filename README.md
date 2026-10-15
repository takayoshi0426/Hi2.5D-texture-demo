# Hi2.5D Environment Studies

外部画像を使わない、Three.jsの土のテクスチャー比較サンプルです。

- 通常のリピート
- 大きな色むらを追加
- 3参照の簡易Hex tiling / stochastic blending

繰り返し回数・凹凸・色むらの調整、視点切替、ドラッグ回転に対応します。

## 開く

[ブラウザーでサンプルを開く](https://takayoshi0426.github.io/Hi2.5D-texture-demo/)

`index.html` をWebGL2対応ブラウザーで開けます。ビルド・サーバー・外部画像は不要です。

## GitHub Pages

Settings → Pages → Build and deployment で `Deploy from a branch`、`main`、`/ (root)` を指定すると、このフォルダを配信できます。

## 構成

公開成果物のHTMLと説明・ライセンス情報のみを収録しています。
Three.jsとビルドツールのライセンスは `THIRD_PARTY_NOTICES.txt` を参照してください。

## 円形闘技場

[直径40mの円形闘技場を開く](https://takayoshi0426.github.io/Hi2.5D-texture-demo/arena.html)

三段の石積み、不揃いな床石、打撃痕・爪痕・焼け跡・補修区画を組み合わせたサンプルです。全景・真上・近景を切り替え、2m・5m・8mの比較模型で大きさを確認できます。

床全体に固有の2Dレイヤーを重ねて生成し、模様をリピートせずに適用しています。`arena.html` も単体で動作し、外部通信は不要です。傷の一部は凹凸の陰影表現で、リアルタイムの破壊や戦闘アニメーションは含みません。
