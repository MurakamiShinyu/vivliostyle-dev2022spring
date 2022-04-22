# Vivliostyleの2022年開発計画を展望する {style="letter-spacing: -0.02em"}

2022-04-23 \
Shinyu Murakami \
Vivliostyle Foundation

# 目次 {.toc role="doc-toc"}

1. [Vivliostyle Pub](#vivliostyle-pub)
  1. [Vivliostyle Pubアルファ版公開](#pub-alpha)

# Vivliostyle Pub {#vivliostyle-pub}

## Vivliostyle Pubアルファ版公開 {#pub-alpha}

CSS組版で本を作るWebアプリVivliostyle Pub、ついに公開！

アルファ版: https://vivliostyle-pub-develop.vercel.app/

ユーザーガイド: https://vivliostyle.github.io/docs-vivliostyle-pub/

![Vivliostyle Pubで執筆中の画面](img/screenshot-vivpub.png){height=200}

## Vivliostyle Pubでできること

- 組版結果をプレビュー確認しながら執筆・編集ができる
- 簡易なマークダウン記法で原稿が書ける
  - [VFM (Vivliostyle Flavored Markdown)](https://vivliostyle.github.io/vfm/#/ja/vfm)
- ページデザインは、テーマから選べる
  - 既存テーマをカスタマイズしたり自分でCSS書いてもよい
- Webフォント対応
- GitHub利用。原稿変更履歴がGitHubに保存される
- 多数の原稿からなる出版物制作、その共同編集作業も可能
- PDF出力、Web出版物(WebBook)、EPUB生成（予定）

## アルファ版の主な制限と、今後の開発

まだアルファ版なので出来ないことや制限が多々あります。<br>
以下は、今は出来ないけれど今後開発予定の機能の主なもの

- EPUB生成
- スタイルテーマの充実とページデザインのカスタマイズ機能
- 印刷用PDFと閲覧用PDFなど、目的別のPDF出力設定
- 目次自動作成
- 索引作成補助
- 表紙・背表紙・裏表紙の作成補助

## Vivliostyle Pubで作った本の印刷製本には

Vivliostyle Pubで作った本の印刷製本がスムーズにできるよう、印刷製本サービスの[mybooks POD](https://pod.mybooks.jp/)<small>（欧文印刷株式会社）</small>と提携。

![Vivliostyle → mybooks PODで印刷製本した本の見本](img/mybookphoto.jpg){height=150}

- Vivliostyle Pubから提携先サービスに繋げるようにする予定
- 印刷製本、電子書籍配信等、提携に関心あればご連絡下さい

## Vivliostyle Pubの開発貢献者たちに感謝！

Vivliostyleの他のプロジェクトと同様、Vivliostyle Pubはオープンソースでボランティアの開発貢献者たちで開発されてます。

![](img/pub-contributors.png){height=330 style="float: right; margin-bottom: -50px"}

開発協力者募集中！

- [Vivliostyle PubのContributorsをGitHubで見る](https://github.com/vivliostyle/vivliostyle-pub/graphs/contributors)

![この2年間のコミットのグラフ](img/pub-contribution.png){height=160 style="margin-left: 0"}<br>
