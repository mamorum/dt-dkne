---
title: CSVの配置
weight: 2
---

## フォルダ・CSV
以下の例のように、フォルダを作成してCSVを配置する必要があります。

{{< filetree/container >}}
  {{< filetree/file name="DtDkne.exe" >}}
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

※ CsvCftには、フォルダと共通形式のCSVを生成する機能があります。

### データフォルダ
デフォルトだと、EXEが配置された場所の `data\daily` がデータフォルダになります。

### データソースフォルダ（例: mb）
名前は半角英数にする必要があります。

### 銘柄フォルダ（例: mb-acwi）
名前は「`データソース-商品識別名`」になります。商品識別名は、半角英数と半角記号を使って付けることができます。

### 共通形式CSV（例: mb-acwi-fmt.csv）
名前は「`銘柄フォルダ名-fmt.csv`」にする必要があります。
