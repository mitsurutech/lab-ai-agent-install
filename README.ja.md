# コーディングエージェントを自分で導入するラボ:opencodeをセットアップしてモデルにつなぎ、テスト付きの小さなプロジェクトで使う

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [日本語](README.ja.md) | [Deutsch](README.de.md)

[![check](https://github.com/mitsurutech/lab-ai-agent-install/actions/workflows/check.yml/badge.svg)](https://github.com/mitsurutech/lab-ai-agent-install/actions/workflows/check.yml)

[MitsuruTechラーニングプラットフォーム](https://mitsurutech.co.uk/learning)が提供する、授業でそのまま使えるラボです。このプラットフォームでは、学校、大学などの教育機関が、すべての学生に専用のデータベース、コンテナ、ターミナルをブラウザ上で提供しています。最初は何もインストールされていないラボです。オープンソースのAIエージェント opencode を自分でインストールし、モデルの場所を教えてから、テスト付きの小さなプロジェクトで使います。

## プラットフォームで使う

**このラボはプラットフォーム上でのみ動きます。** ラボ内のエージェントは、プラットフォームが各学生のコピーのそばに用意するモデルとパッケージプロキシにつながるため、`compose.yaml` は自分のマシンでは単独で起動しません。学生一人ひとりに専用のコピーが渡され、インターネットへの出口はありません。

**試すには:** [コンテナのページ](https://mitsurutech.co.uk/container)を開き、**Sample labs** の中からこのラボを見つけて Start を押します。無料アカウントが必要です。

**クラスの課題として設定するには:**

1. モジュールで、種類が **Lab** のタスクを作り、**In a GitHub repository** を選びます。
2. `https://github.com/mitsurutech/lab-ai-agent-install` とブランチ `main` を指定します。compose ファイルは既定の `compose.yaml` です。変更したい場合は、先にこのリポジトリをフォークしてください。
3. 公開(Publish)します。学生のコピーは公開したコミットから始まるので、あとでここを変更しても、すでに出した課題のラボは変わりません。

ヘルプマニュアルの[このラボのページ](https://mitsurutech.co.uk/help/lab-ai-agent-install)と[コンテナラボのガイド](https://mitsurutech.co.uk/help/labs)に、そのほかの内容があります。対応する基礎レッスンは **AI Coding Agent Basics** です。まだ学校のアカウントがありませんか。[最初の1年間は無料](https://mitsurutech.co.uk/pricing)(学生50人まで)で、[サインアップ](https://mitsurutech.co.uk/signup)にはメールアドレスだけが必要です。

## 知っておくこと

`compose.yaml` の先頭のコメントに、起動の方法とエージェントにできることが書かれています。エージェントは、ファイルを変更したりコマンドを実行したりする前に確認を求めます。やろうとしていることを読み、内容を理解できたときだけ「はい」と答えてください。**何も保存されません**。ラボを止めるとすべてのファイルが消えるので、学生は止める前に自分の作業をダウンロードしてください。AIアシスタントの答えは実行のたびに変わるため、ここでの結果は保証されません。

## ライセンス

この作品は [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) のもとで提供されています。学習と教育のために共有し、改変することができます。ただし、Mitsuru Technologies Ltd のクレジットを表示すること、商用に使わないこと、これをもとに作ったものを同じライセンスで共有することが条件です。全文は `LICENSE` ファイルにあります。

## このリポジトリについて

[Mitsuru Technologies](https://mitsurutech.co.uk) が [MitsuruTechラーニングプラットフォーム](https://mitsurutech.co.uk/learning)のために作りました。学校や大学向けに、Python、Java、Go、Node、SQL、Linux をブラウザ上で使え、コンテナラボ、GitHub からデプロイするWebアプリ、自動採点のクイズも備えています。アカウントなしでコードを試せる[プレイグラウンド](https://mitsurutech.co.uk/playground)もあります。

同じ提供元の、ほかのラボ: [lab-ai-agent](https://github.com/mitsurutech/lab-ai-agent)、[lab-quantum-sim](https://github.com/mitsurutech/lab-quantum-sim)、[lab-jupyter-data](https://github.com/mitsurutech/lab-jupyter-data) と [lab-git-gitea](https://github.com/mitsurutech/lab-git-gitea)。
