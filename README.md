# 使用

文章放在`_posts`目录下，命名为`yyyy-MM-dd-xxxx-xxxx.md`，内容格式如下

```yaml
---
layout: mypost
title: 标题
categories: [分类1, 分类2]
---
文章内容，Markdown格式
```

文章资源放在`posts`目录，如文章文件名是`2019-05-01-theme-usage.md`，则该篇文章的资源需要放在`posts/2019/05/01`下,在文章使用时直接引用即可。当然了，写作的时候会提示资源不存在忽略即可

```md
![这是图片](xxx.png)

[xxx.zip 下载](xxx.zip)
```

# 使用方法

文章は`posts`に置くディレクトリの下で、`yyy-MM-dd-xxxx-xxxx.md`と名付けられた、内容フォーマットは以下の通りです。


```yaml
---
layout: mypost
title:タイトル
categories:[分類1,分類2]
---
記事の内容、Markdown形式
```
文章のリソースは`posts`ディレクトリに置いて、例えば文章のファイル名は`2019-05-01-theme-usage.md`,この文章の資源は`posts/2019/05/01`の下に置く必要があり,文章の使用時に直接引用すればよい.もちろん、書くときはリソースが無視されていないことをヒントにします。

```md
![画像](xxx.png)
[xxx.zip ダウンロード](xxx.zip)
```
