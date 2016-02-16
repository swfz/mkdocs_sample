# MkDocs サンプル

[MkDocs](http://www.mkdocs.org/)にHTMLスライド機能、日本語検索を実装したサンプル

## 追加しているライブラリ

- [lunr-languages](https://github.com/MihaiValentin/lunr-languages)
- [remark.js](http://remarkjs.com/)

## Getting Started
- 下記ドキュメントに従いパッチを当てる
    - README/スライド機能
    - README/日本語検索

## Project layout

```
mkdocs.yml  # The configuration file.
docs/
    index.md # The documentation homepage.
    ...      # Other markdown pages, images and other files.
custom/
    slide.html # remark.js slide page.
patches/
    remark.patch    # remark.jsでのHTMLスライド機能用のパッチ
    search_jp.patch # 日本語検索用のパッチ
    *.js            # 日本語検索用のjsファイル
```

