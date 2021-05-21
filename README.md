# Netflix clone

[【React+TypeScript】Netflixのクローンを作るチュートリアル](https://zenn.dev/gunners6518/books/4c4672f32dd100) をやってみたリポジトリです。

解説記事はこちら

[Netflixのクローンを作るチュートリアルをやってみる - フラミナル](https://blog.framinal.life/entry/2021/05/21/185541)

## API KEY

src/request.js内のAPI KEYは自分のものに書き換えてください

## command

```
# ローカルでの起動
$ yarn start
```

```
# パッケージビルド
$ npm run build 

# firehoseへのデプロイ
$ firehose login --reauth --no-localhost
$ firehose deploy
```