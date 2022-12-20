# Katz Kawai

担当者の Web サイト

## 自己紹介

ゼミの教員です。

## 本サイトについて

卒業制作の成果サイトです。

## ブログ

以下の方法で作成できます。

[Posts の作成](http://jekyllrb-ja.github.io/docs/posts/)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/katz{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## サンプル集

[コンピュータ言語のソースコード](/katz{% link samples.md %})
