# Katz Kawai

担当者のWebサイト

## 自己紹介

ゼミの教員です。

## 本サイトについて

卒業制作の成果サイトです。

## ブログ

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/katz{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## サンプル集

[Link to a page](/katz{% link samples.md %})
