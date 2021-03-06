---
title: "アーリーリターン　〜想定読者を先に宣言するのはどうだろうか？〜"
slug: "early-return-2022-05-07"
date: 2022-05-06T00:00:00Z
draft: false
tags: ["Writing", "Idea"]
---

この文章は、ブログや小説など、文章を書く人向けの内容です。

ブログに限らず、文章を書いていて悩ましいのが **読者層の想定** です。

ニッチ過ぎても読者に届かない……

一般的過ぎてもふわっとした文章になる……

そんなこんなで読者層の範囲を決めるだけでも大変ですが、決めたら決めたで **想定読者層から外れた人をどうするか** という問題が起きます。

例えば、Reactのあるライブラリについて語るとき、ReactやJavaScriptのある程度の知識は前提にしたい場合があります。

素直に書くと、初心者の人にとってはハードルが高すぎる文章になるでしょう。

途中で読むのをやめてくれるならまだマシで、最後まで読んで時間を無駄にしたり、不快感を与えたりする可能性があります。

そこでアーリーリターンです。

アーリーリターンとはプログラムにおいて、最初に例外を弾いておく処理を指します。

Null値かどうかをチェックするIf文とともに現れることが多いです。

```js
function setText(text) {
    if (text === null) {
        return;
    }
    // この後なんかの処理
}
```

大雑把にこんな感じです。

これにヒントを得て、最初に文章の想定読者層を宣言しておく（=外れる人には、注意しておく）というのはありなんじゃないかと思います。

古のホームページでは、トップページに注意書きがあったりしましたが、それが今復活するのかもしれません。
