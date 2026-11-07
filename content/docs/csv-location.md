---
title: CSVの配置
weight: 2
---

以下のフォルダを作成して、CSVを配置していく必要があります。


## データフォルダ
デフォルトだと、EXEが配置された場所の `data\daily` がデータフォルダになります。

{{< filetree/container >}}
  {{< filetree/file name="Dkne.exe" >}}
  {{< filetree/folder name="data" state="open" >}}
    {{< filetree/folder name="daily" state="open" >}}
      {{< filetree/folder name="mb" state="open" >}}
        {{< filetree/folder name="mb-acwi" state="open" >}}
          {{< filetree/file name="mb-acwi-fmt.csv" >}}
        {{< /filetree/folder >}}
      {{< /filetree/folder >}}
    {{< /filetree/folder >}}
  {{< /filetree/folder >}}
{{< /filetree/container >}}

データフォルダ内の要素について、上の例を元に詳細を記載していきます。

### データソースフォルダ（例: mb）
名前は半角英数にする必要があります。

### 銘柄フォルダ（例: mb-acwi）
名前は「`データソース-商品識別名`」になります。商品識別名は、半角英数と半角記号を使って付けることができます。

### CSV（例: mb-acwi-fmt.csv）
名前は「`銘柄名-fmt.csv`」にする必要があります。分析に使用する共通形式のCSVです。
