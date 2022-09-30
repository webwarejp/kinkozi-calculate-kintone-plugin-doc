# サポート関数（カテゴリ別）

<details><summary>日付と時刻の関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [DATE 関数](date-time.md#user-content-date-関数)                       | 特定の日付を表す シリアル値を返します。|
| [DATESTRING 関数](date-time.md#user-content-datestring-関数)           | シリアル値を日付の文字列に変換します。|
| [DATEVALUE 関数](date-time.md#user-content-datevalue-関数)             | 文字列として格納された日付をシリアル値に変換します。| 
| [DAY 関数](date-time.md#user-content-day-関数)                         | 日付の日情報を返します。|
| [DAYS 関数](date-time.md#user-content-days-関数)                       | 2 つの日付間の日数を返します。|
| [DAYS360 関数](date-time.md#user-content-days360-関数)                 | 一部の会計計算に使用される 1 年 360 日の計算方式に基づいて、2 つの日付の間の日数を返します。|
| [EDATE 関数](date-time.md#user-content-edate-関数)                     | 開始日から起算して、指定された月数だけ前または後の日付に対応するシリアル値を返します。|
| [EOMONTH 関数](date-time.md#user-content-eomonth-関数)                 | 開始日から起算して、指定された月数だけ前または後の月の最終日に対応するシリアル値を返します。|
| [HOUR 関数](date-time.md#user-content-hour-関数)                       | 時刻から時間の値を返します。|
| [ISODATESTRING 関数](date-time.md#user-content-isodatestring-関数)     | シリアル値を ISO 8601 の UTC 日付書式に変換します。|
| [ISOWEEKNUM 関数](date-time.md#user-content-isoweeknum-関数)           | 指定された日付のその年における ISO 週番号を返します。|
| [MINUTE 関数](date-time.md#user-content-minute-関数)                   | 時刻の分を返します。 |
| [MONTH 関数](date-time.md#user-content-month-関数)                     | 日付の月を返します。|
| [NETWORKDAYS 関数](date-time.md#user-content-networkdays-関数)         | 開始日から終了日までの期間に含まれる稼動日の日数を返します。| 
| [NETWORKDAYSINTL 関数](date-time.md#user-content-networkdaysintl-関数) | 週末の曜日とその日数を示すパラメーターを使用して、2 つの日付の間の稼働日数を返します。|
| [NOW 関数](date-time.md#user-content-now-関数)                         | 現在を表すシリアル値を返します。|
| [SECOND 関数](date-time.md#user-content-second-関数)                   | 時刻の秒を返します。|
| [TIME 関数](date-time.md#user-content-time-関数)                       | 指定した時刻に対応するシリアル値を返します。|
| [TIMESTRING 関数](date-time.md#user-content-timestring-関数)           | シリアル値を時刻の文字列に変換します。|
| [TIMEVALUE 関数](date-time.md#user-content-timevalue-関数)             | 文字列で表された時刻をシリアル値に変換します。|
| [TODAY 関数](date-time.md#user-content-today-関数)                     | 現在の日付に対応するシリアル値を返します。|
| [WEEKDAY 関数](date-time.md#user-content-weekday-関数)                 | 日付に対応する曜日を返します。|
| [WEEKNUM 関数](date-time.md#user-content-weeknum-関数)                 | 特定の日付が第何週目に当たるかを返します。|
| [WORKDAY 関数](date-time.md#user-content-workday-関数)                 | 開始日から起算して、指定された稼動日数だけ前または後の日付に対応するシリアル値を返します。|
| [WORKDAYINTL 関数](date-time.md#user-content-workdayintl-関数)         | 週末パラメーターを使用して、開始日から起算して指定した稼働日数だけ前または後の日付のシリアル値を返します。|
| [YEAR 関数](date-time.md#user-content-year-関数)                       | 日付に対応する年を返します。|
| [YEARFRAC 関数](date-time.md#user-content-yearfrac-関数)               | 2 つの日付間の期間の数値で表される年の比率を計算します。|

</div></details>

<details><summary>情報関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [ISBLANK 関数](information.md#user-content-isblank-関数)              |テストの対象の値が空のとき TRUE を返します。|
| [ISERROR 関数](information.md#user-content-iserror-関数)              |テストの対象の値がエラーを示す値のとき TRUE を返します。|
| [ISEVEN 関数](information.md#user-content-iseven-関数)                |テストの対象の値が偶数のとき TRUE を返します。|
| [ISODD 関数](information.md#user-content-isodd-関数)                  |テストの対象の値が奇数のとき TRUE を返します。|

</div></details>

<details><summary>論理関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [AND 関数](logical.md#user-content-and-関数)                           | すべての引数が TRUE のときに TRUE を返します。|
| [FALSE 関数](logical.md#user-content-false-関数)                       | 論理値 FALSE を返します。|
| [IF 関数](logical.md#user-content-if-関数)                             | 値または数式が条件を満たしているかどうかを判定します。|
| [IFERROR 関数](logical.md#user-content-iferror-関数)                   | 数式の結果がエラーの場合は指定した値を返し、それ以外の場合は数式の結果を返します。|
| [NOT 関数](logical.md#user-content-not-関数)                           | 引数の論理値を反転させます。|
| [OR 関数](logical.md#user-content-or-関数)                             | いずれかの引数が TRUE のときに TRUE を返します。|
| [SWITCH 関数](logical.md#user-content-switch-関数)                     | 式に対して値の一覧を評価し、最初に一致する値に対応する結果を返します。|
| [TRUE 関数](logical.md#user-content-true-関数)                         | 論理値 TRUE を返します。 |
| [XOR 関数](logical.md#user-content-xor-関数)                           | すべての引数の排他的論理和を返します。|

</div></details>

<details><summary>検索/行列関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [CHOOSE 関数](lookup-matrix.md#user-content-choose-関数)               | 引数リストの値の中から特定の値を 1 つ選択します。|
| [INDEX 関数](lookup-matrix.md#user-content-index-関数)                 | 行番号で指定される配列の要素の値を返します。|
| [ROWS 関数](lookup-matrix.md#user-content-rows-関数)                   | 配列の行数を返します。|

</div></details>

<details><summary>数学関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [ABS 関数](math-trig.md#user-content-abs-関数)                         | 数値の絶対値を返します。|
| [CEILING 関数](math-trig.md#user-content-ceiling-関数)                 | 指定された基準値の倍数のうち、最も近い値に数値を切り上げます。|
| [CEILINGMATH 関数](math-trig.md#user-content-ceilingmath-関数)         | 数値を最も近い整数、または基準値の倍数で最も近い数に切り上げます。|
| [CEILINGPRECISE 関数](math-trig.md#user-content-ceilingprecise-関数)   | 数値を最も近い整数、または基準値の倍数で最も近い数に切り上げます。|
| [DIVIDE 関数](math-trig.md#user-content-divide-関数)                   | 数値を除数で割ったときの商を返します。 |
| [EVEN 関数](math-trig.md#user-content-even-関数)                       | 指定した数値を最も近い偶数に切り上げた数値を返します。|
| [FACT 関数](math-trig.md#user-content-fact-関数)                       | 数値の階乗を返します。|
| [FACTDOUBLE 関数](math-trig.md#user-content-factdouble-関数)           | 数値の二重階乗を返します。|
| [FLOOR 関数](math-trig.md#user-content-floor-関数)                     | 数値を指定された桁数で切り捨てます。|
| [FLOORMATH 関数](math-trig.md#user-content-floormath-関数)             | 指定された基準値の倍数のうち、最も近い値に数値を切り捨てます。|
| [FLOOPRECISE 関数](math-trig.md#user-content-flooprecise-関数)         | 指定された基準値の倍数のうち、最も近い値に数値を切り捨てます。|
| [INT 関数](math-trig.md#user-content-int-関数)                         | 指定された数値を最も近い整数に切り捨てます。|
| [ISOCEILING 関数](math-trig.md#user-content-isoceiling-関数)           | 数値を最も近い整数、または基準値の倍数で最も近い数に切り上げます。|
| [MOD 関数](math-trig.md#user-content-mod-関数)                         | 数値を除数で割ったときの剰余を返します。 |
| [MROUND 関数](math-trig.md#user-content-mround-関数)                   | 指定された値の倍数になるように丸められた数値を返します。|
| [ODD 関数](math-trig.md#user-content-odd-関数)                         | 数値を切り上げて、最も近い奇数にします。|
| [POWER 関数](math-trig.md#user-content-power-関数)                     | 数値のべき乗を返します。|
| [PRODUCT 関数](math-trig.md#user-content-product-関数)                 | 引数として指定されたすべての数値を積算し、その積を返します。|
| [QUOTIENT 関数](math-trig.md#user-content-quotient-関数)               | 除算の商の整数部を返します。|
| [ROUND 関数](math-trig.md#user-content-round-関数)                     | 数値を四捨五入して指定された桁数にします。|
| [ROUNDDOWN 関数](math-trig.md#user-content-rounddown-関数)             | 数値を指定された桁数で切り捨てます。|
| [ROUNDUP 関数](math-trig.md#user-content-roundup-関数)                 | 数値を指定された桁数に切り上げます。|
| [SQRT 関数](math-trig.md#user-content-sqrt-関数)                       | 正の平方根を返します。|
| [SUM 関数](math-trig.md#user-content-sum-関数)                         | 引数を合計します。|
| [SUMIF 関数](math-trig.md#user-content-sumif-関数)                     | 指定した条件を満たす範囲内の値を合計します。|
| [SUMIFS 関数](math-trig.md#user-content-sumifs-関数)                   | 複数の検索条件に一致するすべての引数を合計します。|
| [TRUNC 関数](math-trig.md#user-content-trunc-関数)                     | 数値の小数部を切り捨てて、整数または指定した桁数に変換します。|

</div></details>

<details><summary>統計関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [AVEDEV 関数](stastical.md#user-content-avedev-関数)                   | データ全体の平均値に対するそれぞれのデータの絶対偏差の平均を返します。|
| [AVERAGE 関数](stastical.md#user-content-average-関数)                 | 引数の平均 (算術平均) を返します。|
| [AVERAGEA 関数](stastical.md#user-content-averagea-関数)               | 数値、文字列、および論理値を含む引数の平均値を返します。|
| [AVERAGEIF 関数](stastical.md#user-content-averageif-関数)             | 範囲内の条件に一致するすべての値の平均値 (算術平均) を返します。|
| [AVERAGEIFS 関数](stastical.md#user-content-averageifs-関数)           | 複数の範囲内の条件に一致するすべての値の平均値 (算術平均) を返します。|
| [COUNT 関数](stastical.md#user-content-count-関数)                     | 引数リストの各項目に含まれる数値の個数を返します。|
| [COUNTA 関数](stastical.md#user-content-counta-関数)                   | 範囲に含まれる空白ではない引数リストに含まれる数値の個数を返します。|
| [COUNTBLANK 関数](stastical.md#user-content-countblank-関数)           | 指定された範囲に含まれる空白フィールドの個数を返します。|
| [COUNTIF 関数](stastical.md#user-content-countif-関数)                 | 1 つの検索条件に一致する範囲内のフィールドの個数を返します。|
| [COUNTIFS 関数](stastical.md#user-content-countifs-関数)               | 複数の検索条件に一致する範囲内のフィールドの個数を返します。|
| [LARGE 関数](stastical.md#user-content-large-関数)                     | 指定されたデータの中で k 番目に大きなデータを返します。|
| [MAX 関数](stastical.md#user-content-max-関数)                         | 一連の引数のうち、最大の数値を返します。|
| [MAXIFS 関数](stastical.md#user-content-maxifs-関数)                   | 条件セットで指定されたデータの中の最大値を返します。|
| [MODE.SNGL 関数](stastical.md#user-content-modesngl-関数)              | 引数リストに含まれる数値データの中で、最も頻繁に出現する値 (モード) を返します。|
| [MODE.MULT 関数](stastical.md#user-content-modemult-関数)              | 引数リストに含まれる数値データの中で、最も頻繁に出現する値 (モード) を配列で返します。|
| [MEDIAN 関数](stastical.md#user-content-median-関数)                   | 引数リストに含まれる数値のメジアン (中央値) を返します。|
| [MIN 関数](stastical.md#user-content-min-関数)                         | 一連の引数のうち、最小の数値を返します。|
| [MINIFS 関数](stastical.md#user-content-minifs-関数)                   | 条件セットで指定されたデータの中の最小値を返します。|
| [PERCENTILEEXC 関数](stastical.md#user-content-percentileexc-関数)     | 特定の範囲に含まれるデータの第 k 百分位数に当たる値を返します (k は 0 より大きく 1 より小さい値)。|
| [PERCENTILEINC 関数](stastical.md#user-content-percentileinc-関数)     | 特定の範囲に含まれるデータの第 k 百分位数に当たる値を返します。|
| [PERCENTRANKEXC 関数](stastical.md#user-content-percentrankexc-関数)   | 配列内での値の順位を百分率 (0 より大きく 1 より小さい) で返します。|
| [PERCENTRANKINC 関数](stastical.md#user-content-percentrankinc-関数)   | 配列内での値の順位を百分率 (0 ～ 1、0 および 1 を含む) で返します。|
| [QUARTILEEXC 関数](stastical.md#user-content-quartileexc-関数)         | 0 ～ 1 の間 (0 および 1 を除く) の百分率の値に基づいて、データの配列の四分位数を返します。|
| [QUARTILEINC 関数](stastical.md#user-content-quartileinc-関数)         | 0 ～ 1 の間 (0 および 1 を含む) の百分率の値に基づいて、データの配列の四分位数を返します。|
| [RANK.AVG 関数](stastical.md#user-content-rankavg-関数)                | 数値のリストの中で、指定した数値の序列を返します。|
| [RANK.EQ 関数](stastical.md#user-content-rankeq-関数)                  | 数値のリストの中で、指定した数値の序列を返します。|
| [SMALL 関数](stastical.md#user-content-small-関数)                     | 指定されたデータの中で、k 番目に小さなデータを返します。 |
| [STDEV.P 関数](stastical.md#user-content-stdevp-関数)                  | 引数を母集団全体と見なし、母集団の標準偏差を返します。|
| [STDEV.S 関数](stastical.md#user-content-stdevs-関数)                  | 引数を正規母集団の標本と見なし、標本に基づいて母集団の標準偏差の推定値を返します。|
| [TRIMMEAN 関数](stastical.md#user-content-trimmean-関数)               | データの中間項の平均を返します。|
| [VAR.P 関数](stastical.md#user-content-varp-関数)                      | 引数を母集団全体と見なし、母集団の分散 (標本分散) を返します。|
| [VAR.S 関数](stastical.md#user-content-vars-関数)                      | 標本に基づいて母集団の分散の推定値 (不偏分散) を返します。|

</div></details>

<details><summary>文字列関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [CHAR 関数](text.md#user-content-char-関数)                            | 数値で指定された文字を返します。|
| [CODE 関数](text.md#user-content-code-関数)                            | テキスト文字列内の先頭文字の数値コードを返します。|
| [CONCAT 関数](text.md#user-content-concat-関数)                        | 複数の文字列を結合して 1 つの文字列にまとめます。|
| [CONCATENATE 関数](text.md#user-content-concatenate-関数)              | 複数の文字列を結合して 1 つの文字列にまとめます。|
| [DOLLAR 関数](text.md#user-content-dollar-関数)                        | 数値を四捨五入し、通貨書式を設定した文字列に変換します。|
| [EXACT 関数](text.md#user-content-exact-関数)                          | 2 つの文字列が等しいかどうかを判定します。|
| [FIND 関数](text.md#user-content-find-関数)                            | 指定された文字列を他の文字列の中で検索します。|
| [FIXED 関数](text.md#user-content-fixed-関数)                          | 数値を四捨五入し、書式設定した文字列に変換します。|
| [LEFT 関数](text.md#user-content-left-関数)                            | 文字列の先頭から指定された数の文字を返します。|
| [LEN 関数](text.md#user-content-len-関数)                              | 文字列の文字数を返します。|
| [LOWER 関数](text.md#user-content-lower-関数)                          | 文字列に含まれる英大文字をすべて小文字に変換します。|
| [MID 関数](text.md#user-content-mid-関数)                              | 文字列の指定された位置から指定された文字数の文字を返します。|
| [PROPER 関数](text.md#user-content-proper-関数)                        | 文字列に含まれる英単語の先頭文字だけを大文字に変換します。|
| [REPLACE 関数](text.md#user-content-replace-関数)                      | 文字列中の指定された数の文字を他の文字に置き換えます。|
| [REPT 関数](text.md#user-content-rept-関数)                            | 文字列を指定された回数だけ繰り返して表示します。|
| [RIGHT 関数](text.md#user-content-right-関数)                          | 文字列の末尾 (右端) から指定された文字数の文字を返します。|
| [SEARCH 関数](text.md#user-content-search-関数)                        | 指定された文字列を他の文字列の中で検索します。大文字と小文字は区別されません。|
| [SUBSTITUTE 関数](text.md#user-content-substitute-関数)                | 文字列中の指定された文字を他の文字に置き換えます。|
| [TEXTJOIN 関数](text.md#user-content-textjoin-関数)                    | 複数の範囲や文字列からのテキストを結合し、結合する各テキスト値の間に指定した区切り記号を挿入します。|
| [TRIM 関数](text.md#user-content-trim-関数)                            | 文字列から余分なスペースを削除します。|
| [UPPER 関数](text.md#user-content-upper-関数)                          | 文字列を大文字に変換します。|
| [YEN 関数](text.md#user-content-yen-関数)                              | 数値を四捨五入し、通貨書式を設定した文字列に変換します。|

</div></details>

<details><summary>その他の関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [UNIQUE 関数](miscellaneous.md#user-content-unique-関数)               | 重複しない値を抽出します。|
| [NULL 関数](miscellaneous.md#user-content-null-関数)                   | NULL を返します。|

</div></details>