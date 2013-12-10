---
lang: ja
layout: quickstart
meta_title: Ghost Quickstart
heading: Ghost Quickstart
subheading: Get up and running with Ghost.
chapter: quickstart
section: quickstart
---

# 概要 <a id="overview"></a>

クイックスタートガイドは既に [Node](http://nodejs.org) ruby on rails のような環境に慣れている人を対象としています。もしもこういった環境を使うのが初めてであれば、[インストールガイド](/installation.html)をまず参照することをおすすめします。

## ローカル環境で Ghost を動かす <a id="ghost-local"></a>

Ghost を動かすには node `0.10.*` が必要です。(最新の安定版バージョン)

上記のバージョンを動かせる環境でない場合は、まず <http://nodejs.org> へ行き、最新の Node.js をダウンロードしてください。インストーラを使用することにより、 Node と Node の素晴らしいパッケージマネージャである npm がインストールされます。

Linux ユーザは .tar.gz のアーカイブファイルからのインストールよりも [パッケージマネージャを使用したインストール](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager) を好むかもしれません。

[Ghost.org](http://ghost.org) より、最新バージョンの Ghost をダウンロードしてください。アーカイブファイルを Ghost を実行したいファイルに展開してくださ。(どこでも構いません!)

ターミナル画面(mac/linux) もしくは コマンドプロンプト画面(windows) を開き、Ghost アーカイブファイルを展開したディレクトリまで移動してください。(package.jsonがあるディレクトリです)

Ghost をインストールするために、 `npm install --production` を実行してください。

<!--<h2 id="customise">Ghost の設定とカスタマイズ</h2>

<h2 id="ghost-deploy">Ghost のデプロイ</h2>

<ol>
    <li>ターミナル画面 もしくは コマンドプロンプト画面で、<code>npm start</code> とタイプしてください。</li>
    <li><p>こうすることで、あなたの Ghost blog が動きます。<a href="http://localhost:2368/">http://localhost:2368/</a>へアクセスして確認してみてください。</p></li>
</ol>
-->
