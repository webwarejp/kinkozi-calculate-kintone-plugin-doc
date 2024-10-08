# カテゴリ: 検索/行列関数

## CHOOSE 関数

インデックスを使用して、値引数のリストから値を返します。CHOOSE 関数を使用すると、インデックス番号に基づいて最大 254 個の値から 1 つを選択することができます。たとえば、値 1 ～値 7 が曜日を表す場合、1 ～ 7 のいずれかの数値をインデックスとして使用すると、該当する曜日が返されます。

### 書式

    CHOOSE(インデックス, 値 1, [値 2], ...)

| 引数       | 説明         |
|:-----------|:------------|
|インデックス| 必須。どの値引数が選択されるかを指定します。インデックスには 1 ～ 254 の数値、または 1 ～ 254 の数値を返す数式または数値か計算のフィールドコードを指定します。|
|値 1, [値 2], ...|値 1 は必ず指定し、数値 2 以降は省略可能です。1 ～ 254 個の値引数を指定します。CHOOSE 関数はこれらの引数から、インデックスに基づいて 1 つの値または実行する動作を選択します。引数には、数値、フィールドコード、数式、関数、または文字列を指定できます。|

## INDEX 関数

行番号で指定される配列の要素の値を返します。

### 書式

    INDEX(配列, 行番号, [列番号])

| 引数       | 説明         |
|:-----------|:------------|
|配列         |必須。サブテーブル内のフィールドコード、関連レコード一覧内のフィールドコード、または配列定数を指定します。|
|行番号       |必須。値を返す行を数値で指定します。|
|列番号       |省略可能。値を返す列を数値で指定します。|

* 配列に配列定数を指定した場合、配列は二次元配列とみなされるため、列番号を省略すると配列オブジェクトが返されます。
* 配列にサブテーブル内のフィールドコード、または関連レコード一覧内のフィールドコードを指定した場合、列番号を指定しても無視されます。

## ROWS 関数

配列の行数を返します。

### 書式

    ROWS(配列)

| 引数       | 説明         |
|:-----------|:------------|
|配列        |必須。行数を求める配列。配列定数、サブテーブル内のフィールドコード、または関連レコード一覧内のフィールドコードが指定できます。|

## UNIQUE 関数

重複しない値を抽出します。

### 書式

    UNIQUE(値 1, [値 2], ...)

| 引数       | 説明         |
|:-----------|:------------|
|値 1       |必須。最初の値。数値、文字列、配列定数、またはフィールドコードが指定できます。|
|[値 2], ...|省略可能。重複を確認する 2 番目以降の数値です。数値、文字列、またはフィールドコードが指定できます。|

* 引数には、サブテーブル内のフィールドコード、関連レコード一覧内のフィールドコードも指定できます。
* 戻り値が配列オブジェクトとなるため、計算式の中で使用してください。

<br />

[サポート関数（カテゴリ別）](category-list.md)  
[トップページ](index.md)