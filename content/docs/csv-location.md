---
title: CSVの配置
weight: 2
---

CsvCftでCSVを選択して変換すると、以下のフォルダと共通形式のCSVが生成されます。

※ 手動でフォルダを作成して、CSVを配置することもできます。


## フォルダ・CSV
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

### データフォルダ
デフォルトだと、EXEが配置された場所の `data\daily` がデータフォルダになります。

### データソースフォルダ（例: mb）
名前は半角英数にする必要があります。

### 銘柄フォルダ（例: mb-acwi）
名前は「`データソース名-商品識別名`」で、商品識別名には半角英数と半角記号が使用できます。

### 共通形式CSV（例: mb-acwi-fmt.csv）
名前は「`銘柄フォルダ名-fmt.csv`」にする必要があります。
