---
title: "いつの間にか Github Actions のデフォルト設定が変わっていました"
slug: "github-actions-default-setting-2022-05-04"
date: 2022-05-04
draft: false
tags: ["GithubActions", "YAML", "Fix"]
---

新しく _Hugo_ のウェブサイト（つまり、このサイト）を作ろうと思って、

_peaceiris_ さんの _yml_ ファイルを使ったけどエラー。

原因は _Github Actions_ のデフォルトの設定で書き込みが容認されてなかったからでした。

![スクショ](./2022-05-04_screen_1.png)

Githubの設定画面で、

![スクショ](./2022-05-04_screen_2.png)

Workflow Permissionsの設定を変える。

当初、理由がいまいち分からずあちこち検索したが、

Web上にはクリティカルなものは無いみたい。

なのでここに記録しておきます。
