# 一般ユーザ向けコマンド

- [一般ユーザ向けコマンド](#一般ユーザ向けコマンド)
  - [基本系](#基本系)
    - [`omikuji`](#omikuji)
    - [`vote <タイトル> <投票1> [投票2]...`](#vote-タイトル-投票1-投票2)
    - [`random <試行回数> <選択肢1> [選択肢2]...`](#random-試行回数-選択肢1-選択肢2)
    - [`help`](#help)
    - [`help-<pageID>`](#help-pageid)
  - [詳細系](#詳細系)
    - [`ping`](#ping)
    - [`about`](#about)
    - [`status`](#status)
    - [`version`](#version)
    - [`license`](#license)
    - [`user <ユーザーID|ユーザーメンション>`](#user-ユーザーidユーザーメンション)
  - [設定系](#設定系)
    - [`one-day-kuji`](#one-day-kuji)
    - [`one-day-tawasi`](#one-day-tawasi)
    - [`profile-update`](#profile-update)
    - [`set-prefix <設定したいprefix>`](#set-prefix-設定したいprefix)
  - [管理系](#管理系)

---

## 基本系

### `omikuji`

おみくじをします。

### `vote <タイトル> <投票1> [投票2]...`

投票を行います。

### `random <試行回数> <選択肢1> [選択肢2]...`

抽選を行います。

### `help`

最初のヘルプを表示します。

### `help-<pageID>`

指定したページIDのヘルプを表示します。

## 詳細系

システムに関するコマンド

### `ping`

ping値[ms]を表示します。

### `about`

Namagomi-botの情報を表示します。

### `status`

Namagomi-botのステータスを表示します。

### `version`

Namagomi-botのバージョンを表示します。

### `license`

Namagomi-botのライセンスを表示します。

### `user <ユーザーID|ユーザーメンション>`

ユーザー情報を表示します。

## 設定系

### `one-day-kuji`

おみくじを1日1回のみにするかどうかを設定します。

### `one-day-tawasi`

1日1たわしさんを有効にするかどうかを設定します。

### `profile-update`

プロフィールを最新の状態に更新します。

### `set-prefix <設定したいprefix>`

コマンドの接頭辞を設定します。
本コマンドを実施したユーザーのみコマンドの接頭辞設定が反映されます。

## 管理系

管理者のみ実行可能なコマンドです。

[管理者向けコマンドページ](../admin/admin-command.md)を参照。

