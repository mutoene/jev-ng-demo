# jev-ng-demo

入力した文章に不適切な表現が含まれているかを、TypeSafe の判定モデル jev で判定するデモページ。

https://mutoene.github.io/jev-ng-demo/

このリポジトリにあるのはページ（`index.html`）だけで、判定 API は Cloudflare Worker
（`https://jev-ng-demo.liminality.workers.dev`）が返す。入力した文章と判定結果は、判定の改善用データとして保存される。
