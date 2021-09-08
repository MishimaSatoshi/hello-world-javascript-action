# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## 入力

### `who-to-greet`

**必須** 挨拶する相手の名前。 デフォルトは `"World"`。

## 出力

### `time`

挨拶した時間。

## 使用例

uses: actions/hello-world-javascript-action@v1.1
with:
  who-to-greet: 'Mona the Octocat'