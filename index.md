# Katz Kawai

担当者の Web サイト（あくまでもサンプル。一例です。）

## 自己紹介

ゼミの教員です。

## 本サイトについて

卒業制作の成果サイトです。作品は[個人のレポジトリ](https://katzkawai.github.io/)に掲載しています。

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

[Link to a page](/katz{% link samples.md %})

## 卒業制作

[個人のレポジトリ](https://katzkawai.github.io/)に掲載しています。
