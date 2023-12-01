---
layout: default
title: pacup
parent: コマンドリファレンス
has_children: false
nav_exclude: false
search_exclude: false
has_toc: false
---

TODO: update、full-upgrade、autoremoveの説明
TODO: autoremoveの、--fix-brokenオプションに関する説明
TODO: そもそもapt-getとaptの違いは何か？歴史的経緯の掲載場所

## pacupコマンドとは

Debianが提供する「apt-getコマンド」を用いて、下記3種類のものを一括で実行します。
apt-getはパッケージ

* apt-get update
* apt-get full-upgrade
* apt-get autoremove --fix-broken

open.Yellow.osは、ディストリビューション「Debian」をベースとしたLinuxです(2023年現在)

### apt-get updateとは

ディストリビューションが提供するパッケージのうち、更新可能なソフトウェアのリストを更新します。更新できるソフトウェアの一覧を更新するだけで、パッケージそのものは

3回コマンドを叩かないといけなかったものを、pacupコマンドでは全て一括実行致します。

Debianが提供するパッケージ(ソフトウェア)

## その他

 --fix-broken 修復 - 依存関係が壊れたシステムの修正を試みます。

オプション自体は他にもありますが、そちらはソースをご参照頂けたらと思います。

[https://github.com/openyellowos/pacup/blob/main/pacup]("packup ソース")
