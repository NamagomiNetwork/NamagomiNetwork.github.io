# 管理者向けコマンド

- [管理者向けコマンド](#管理者向けコマンド)
  - [`eval <評価したいJavaScriptコード>`](#eval-評価したいjavascriptコード)
  - [`shell <実行したいshellコマンド>`](#shell-実行したいshellコマンド)
  - [`reload <コマンド名>`](#reload-コマンド名)
  - [`check <ユーザーID|ユーザーメンション>`](#check-ユーザーidユーザーメンション)
  - [`shutdown`](#shutdown)
  - [`reset-tawasi <ユーザーID>`](#reset-tawasi-ユーザーid)
  - [`prefix-reset <ユーザーID>`](#prefix-reset-ユーザーid)
  - [`block <ユーザーID>`](#block-ユーザーid)
  - [`unblock <ユーザーID>`](#unblock-ユーザーid)
  - [`hardblock <ユーザーID>`](#hardblock-ユーザーid)
  - [`unhardblock <ユーザーID>`](#unhardblock-ユーザーid)
  - [`deploy`](#deploy)


## `eval <評価したいJavaScriptコード>`

JavaScriptコードを評価します。

## `shell <実行したいshellコマンド>`

shellコマンドを実行します。

## `reload <コマンド名>`

コマンドをリロードします。

## `check <ユーザーID|ユーザーメンション>`

DBに保存されているユーザーデータを表示します。

## `shutdown`

Namagomi-botをシャットダウンします。

## `reset-tawasi <ユーザーID>`

ユーザーの1日1たわしをリセットします。

## `prefix-reset <ユーザーID>`

コマンドの接頭辞設定をリセットします。

Namagomi-botの`config.json`により設定されている接頭辞設定が反映されます。


## `block <ユーザーID>`

ユーザーのブロックを行い、コマンド実行を禁止します。

## `unblock <ユーザーID>`

ユーザーのブロックを解除します。

## `hardblock <ユーザーID>`

`block`コマンドと同様、ユーザーのハードブロックを行い、コマンドの実行を禁止します。

ユーザーのハードブロック状態におけるコマンド実行時、ブロックされていることを通知するメッセージを表示しません。

## `unhardblock <ユーザーID>`

ユーザーのハードブロックを解除します。

## `deploy`

`git pull origin main`を実行します。

`g!shell git pull origin main`を簡便にした、エイリアスコマンド
