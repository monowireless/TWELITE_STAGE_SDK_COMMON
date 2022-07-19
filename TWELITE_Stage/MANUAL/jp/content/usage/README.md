---
title: "使用方法"
author: "Mono Wireless Inc."
description: operation manual
---

# 使用方法

TWELITE STAGE アプリ の画面・操作方法の解説です。

## 実行について

TWELITE STAGE アプリを起動するには `{MWSTAGE インストール}` にある実行形式を実行します。

実行は各システム(Windows, macOS, Linux)ごとに方法が違います。

| システム | ファイル拡張子 | 備考 |
| -------- | ------     | ---- |
| Windows  | `.exe`     | エクスプローラで実行形式をダブルクリック。 |
| macOS    | `.command` | ファインダーから実行形式をダブルクリック。 |
| Linux, RaspberryPi | `.run`     | ディストリビューションやインストール環境に依存します。Xウインドウシステム上のターミナル画面(xtermなど)から、コマンドとして実行します |


## 実行形式について

２種類の実行形式を用意しています。

* TWELITE_Stage.{拡張子} - 標準設定で起動します
* TWELITE_Stage_VSCode.{拡張子} - 「VSCode を使う」設定済みです(設定は`TWELITE_Stage_VSCode.ini`に保存されている)。VSCodeを使う設定を有効にすると、VSCodeを用いた開発作業に適した動作を行うようになります。

{% hint style="warning" %}
TWELITE STAGE アプリは複数起動してもエラーになりませんが、複数起動すると不都合のある機能（センサーグラフ機能など）が存在します。

この場合、実行形式のコピーを作成して、別のファイル名として起動します。各種設定や入出力ファイルのファイル名が別になり、互いの干渉がなくなります。
{% endhint %}

## 実行画面について

実行中の画面は２種類あります。１つはコマンド画面（コマンド画面から起動した場合は、そのコマンド画面）、１つは TWELITE STAGE のメイン画面です。コマンド画面は、動作確認など補助情報を確認できますが通常は使用しません。

![STAGE画面例](../.gitbook/assets/img_stage_open_with_cmdwin.png)

