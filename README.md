### さらっと静的ページを作るのに使えそうなやつ
Eleventy(11ty)で手軽に静的ページを作れる環境
テンプレートは11tyのドキュメントに例が一番多いNunjucksを採用

### 開発環境について
最初やるやつ
- `npm install`

開発する際はこれ
- `npm start` or `npm run dev`

ビルドする場合
- `npm run build`

### 開発
`npm start` or `npm run dev` で開始したら、 `src` ディレクトリにあるファイルをいじって開発  
`src/_data/site.js` にサイトのmetaとかまとめてるので適宜修正
