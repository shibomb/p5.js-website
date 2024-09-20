# p5.js Website Japanese version.

## build search index before

npm run build:search

# translation with AI

0. open project on Cursor Editor.
1. open file (e.g. .mdx).
2. chat this prompt with claude-3.5-sonnet in chat window.

```
文章の部分を忠実に日本語に翻訳してください。
title: , module: , submodule: ,file: の部分はそのままにしてください。
HTMLタグを壊さないように気をつけてください。
マークダウンの書式や制御用のコメントは絶対に壊さないように気をつけてください。
example: の部分はソースコードなので壊さないように気をつけてほしいですが、コメント部分は翻訳してください。

ファイル毎にソースファイルとしてコピー＆ペーストしやすいようにまとめて出力してください。

ファイルの最後まで実行し続けてください。
全ての対象ファイルが完了するまで次々と続けてください。
```

3. Copy result and paset to file.
