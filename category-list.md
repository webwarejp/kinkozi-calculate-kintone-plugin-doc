# サポート関数（カテゴリ別）

<details><summary>日付と時刻の関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [DATE 関数](date-time.md#date-)                       | 特定の日付を表す シリアル値を返します。|
| [DATESTRING 関数](date-time.md#datestring-)           | シリアル値を日付の文字列に変換します。|
| [DATEVALUE 関数](date-time.md#datevalue-)             | 文字列として格納された日付をシリアル値に変換します。| 
| [DAY 関数](date-time.md#day-)                         | 日付の日情報を返します。|
| [DAYS 関数](date-time.md#days-)                       | 2 つの日付間の日数を返します。|
| [DAYS360 関数](date-time.md#days360-)                 | 一部の会計計算に使用される 1 年 360 日の計算方式に基づいて、2 つの日付の間の日数を返します。|
| [EDATE 関数](date-time.md#edate-)                     | 開始日から起算して、指定された月数だけ前または後の日付に対応するシリアル値を返します。|
| [EOMONTH 関数](date-time.md#eomonth-)                 | 開始日から起算して、指定された月数だけ前または後の月の最終日に対応するシリアル値を返します。|
| [HOUR 関数](date-time.md#hour-)                       | 時刻から時間の値を返します。|
| [ISODATESTRING 関数](date-time.md#isodatestring-)     | シリアル値を ISO 8601 の UTC 日付書式に変換します。|
| [ISOWEEKNUM 関数](date-time.md#isoweeknum-)           | 指定された日付のその年における ISO 週番号を返します。|
| [MINUTE 関数](date-time.md#minute-)                   | 時刻の分を返します。 |
| [MONTH 関数](date-time.md#month-)                     | 日付の月を返します。|
| [NETWORKDAYS 関数](date-time.md#networkdays-)         | 開始日から終了日までの期間に含まれる稼動日の日数を返します。| 
| [NETWORKDAYSINTL 関数](date-time.md#networkdaysintl-) | 週末の曜日とその日数を示すパラメーターを使用して、2 つの日付の間の稼働日数を返します。|
| [NOW 関数](date-time.md#now-)                         | 現在を表すシリアル値を返します。|
| [SECOND 関数](date-time.md#second-)                   | 時刻の秒を返します。|
| [TIME 関数](date-time.md#time-)                       | 指定した時刻に対応するシリアル値を返します。|
| [TIMESTRING 関数](date-time.md#timestring-)           | シリアル値を時刻の文字列に変換します。|
| [TIMEVALUE 関数](date-time.md#timevalue-)             | 文字列で表された時刻をシリアル値に変換します。|
| [TODAY 関数](date-time.md#today-)                     | 現在の日付に対応するシリアル値を返します。|
| [WEEKDAY 関数](date-time.md#weekday-)                 | 日付に対応する曜日を返します。|
| [WEEKNUM 関数](date-time.md#weeknum-)                 | 特定の日付が第何週目に当たるかを返します。|
| [WORKDAY 関数](date-time.md#workday-)                 | 開始日から起算して、指定された稼動日数だけ前または後の日付に対応するシリアル値を返します。|
| [WORKDAYINTL 関数](date-time.md#workdayintl-)         | 週末パラメーターを使用して、開始日から起算して指定した稼働日数だけ前または後の日付のシリアル値を返します。|
| [YEAR 関数](date-time.md#year-)                       | 日付に対応する年を返します。|
| [YEARFRAC 関数](date-time.md#yearfrac-)               | 2 つの日付間の期間の数値で表される年の比率を計算します。|

</div></details>

<details><summary>情報関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [ISBLANK 関数](information.md#isblank-)              |テストの対象の値が空のとき TRUE を返します。|
| [ISERROR 関数](information.md#iserror-)              |テストの対象の値がエラーを示す値のとき TRUE を返します。|
| [ISEVEN 関数](information.md#iseven-)                |テストの対象の値が偶数のとき TRUE を返します。|
| [ISODD 関数](information.md#isodd-)                  |テストの対象の値が奇数のとき TRUE を返します。|

</div></details>

<details><summary>論理関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [AND 関数](logical.md#and-)                           | すべての引数が TRUE のときに TRUE を返します。|
| [FALSE 関数](logical.md#false-)                       | 論理値 FALSE を返します。|
| [IF 関数](logical.md#if-)                             | 値または数式が条件を満たしているかどうかを判定します。|
| [IFERROR 関数](logical.md#iferror-)                   | 数式の結果がエラーの場合は指定した値を返し、それ以外の場合は数式の結果を返します。|
| [NOT 関数](logical.md#not-)                           | 引数の論理値を反転させます。|
| [OR 関数](logical.md#or-)                             | いずれかの引数が TRUE のときに TRUE を返します。|
| [SWITCH 関数](logical.md#switch-)                     | 式に対して値の一覧を評価し、最初に一致する値に対応する結果を返します。|
| [TRUE 関数](logical.md#true-)                         | 論理値 TRUE を返します。 |
| [XOR 関数](logical.md#xor-)                           | すべての引数の排他的論理和を返します。|

</div></details>

<details><summary>検索/行列関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [CHOOSE 関数](lookup-matrix.md#choose-)               | 引数リストの値の中から特定の値を 1 つ選択します。|
| [INDEX 関数](lookup-matrix.md#index-)                 | 行番号で指定される配列の要素の値を返します。|
| [ROWS 関数](lookup-matrix.md#rows-)                   | 配列の行数を返します。|

</div></details>

<details><summary>数学関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [ABS 関数](math-trig.md#abs-)                         | 数値の絶対値を返します。|
| [CEILING 関数](math-trig.md#ceiling-)                 | 指定された基準値の倍数のうち、最も近い値に数値を切り上げます。|
| [CEILINGMATH 関数](math-trig.md#ceilingmath-)         | 数値を最も近い整数、または基準値の倍数で最も近い数に切り上げます。|
| [CEILINGPRECISE 関数](math-trig.md#ceilingprecise-)   | 数値を最も近い整数、または基準値の倍数で最も近い数に切り上げます。|
| [DIVIDE 関数](math-trig.md#divide-)                   | 数値を除数で割ったときの商を返します。 |
| [EVEN 関数](math-trig.md#even-)                       | 指定した数値を最も近い偶数に切り上げた数値を返します。|
| [FACT 関数](math-trig.md#fact-)                       | 数値の階乗を返します。|
| [FACTDOUBLE 関数](math-trig.md#factdouble-)           | 数値の二重階乗を返します。|
| [FLOOR 関数](math-trig.md#floor-)                     | 数値を指定された桁数で切り捨てます。|
| [FLOORMATH 関数](math-trig.md#floormath-)             | 指定された基準値の倍数のうち、最も近い値に数値を切り捨てます。|
| [FLOOPRECISE 関数](math-trig.md#flooprecise-)         | 指定された基準値の倍数のうち、最も近い値に数値を切り捨てます。|
| [INT 関数](math-trig.md#int-)                         | 指定された数値を最も近い整数に切り捨てます。|
| [ISOCEILING 関数](math-trig.md#isoceiling-)           | 数値を最も近い整数、または基準値の倍数で最も近い数に切り上げます。|
| [MOD 関数](math-trig.md#mod-)                         | 数値を除数で割ったときの剰余を返します。 |
| [MROUND 関数](math-trig.md#mround-)                   | 指定された値の倍数になるように丸められた数値を返します。|
| [ODD 関数](math-trig.md#odd-)                         | 数値を切り上げて、最も近い奇数にします。|
| [POWER 関数](math-trig.md#power-)                     | 数値のべき乗を返します。|
| [PRODUCT 関数](math-trig.md#product-)                 | 引数として指定されたすべての数値を積算し、その積を返します。|
| [QUOTIENT 関数](math-trig.md#quotient-)               | 除算の商の整数部を返します。|
| [ROUND 関数](math-trig.md#round-)                     | 数値を四捨五入して指定された桁数にします。|
| [ROUNDDOWN 関数](math-trig.md#rounddown-)             | 数値を指定された桁数で切り捨てます。|
| [ROUNDUP 関数](math-trig.md#roundup-)                 | 数値を指定された桁数に切り上げます。|
| [SQRT 関数](math-trig.md#sqrt-)                       | 正の平方根を返します。|
| [SUM 関数](math-trig.md#sum-)                         | 引数を合計します。|
| [SUMIF 関数](math-trig.md#sumif-)                     | 指定した条件を満たす範囲内の値を合計します。|
| [SUMIFS 関数](math-trig.md#sumifs-)                   | 複数の検索条件に一致するすべての引数を合計します。|
| [TRUNC 関数](math-trig.md#trunc-)                     | 数値の小数部を切り捨てて、整数または指定した桁数に変換します。|

</div></details>

<details><summary>統計関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [AVEDEV 関数](stastical.md#avedev-)                   | データ全体の平均値に対するそれぞれのデータの絶対偏差の平均を返します。|
| [AVERAGE 関数](stastical.md#average-)                 | 引数の平均 (算術平均) を返します。|
| [AVERAGEA 関数](stastical.md#averagea-)               | 数値、文字列、および論理値を含む引数の平均値を返します。|
| [AVERAGEIF 関数](stastical.md#averageif-)             | 範囲内の条件に一致するすべての値の平均値 (算術平均) を返します。|
| [AVERAGEIFS 関数](stastical.md#averageifs-)           | 複数の範囲内の条件に一致するすべての値の平均値 (算術平均) を返します。|
| [COUNT 関数](stastical.md#count-)                     | 引数リストの各項目に含まれる数値の個数を返します。|
| [COUNTA 関数](stastical.md#counta-)                   | 範囲に含まれる空白ではない引数リストに含まれる数値の個数を返します。|
| [COUNTBLANK 関数](stastical.md#countblank-)           | 指定された範囲に含まれる空白フィールドの個数を返します。|
| [COUNTIF 関数](stastical.md#countif-)                 | 1 つの検索条件に一致する範囲内のフィールドの個数を返します。|
| [COUNTIFS 関数](stastical.md#countifs-)               | 複数の検索条件に一致する範囲内のフィールドの個数を返します。|
| [LARGE 関数](stastical.md#large-)                     | 指定されたデータの中で k 番目に大きなデータを返します。|
| [MAX 関数](stastical.md#max-)                         | 一連の引数のうち、最大の数値を返します。|
| [MAXIFS 関数](stastical.md#maxifs-)                   | 条件セットで指定されたデータの中の最大値を返します。|
| [MODE.SNGL 関数](stastical.md#modesngl-)              | 引数リストに含まれる数値データの中で、最も頻繁に出現する値 (モード) を返します。|
| [MODE.MULT 関数](stastical.md#modemult-)              | 引数リストに含まれる数値データの中で、最も頻繁に出現する値 (モード) を配列で返します。|
| [MEDIAN 関数](stastical.md#median-)                   | 引数リストに含まれる数値のメジアン (中央値) を返します。|
| [MIN 関数](stastical.md#min-)                         | 一連の引数のうち、最小の数値を返します。|
| [MINIFS 関数](stastical.md#minifs-)                   | 条件セットで指定されたデータの中の最小値を返します。|
| [PERCENTILEEXC 関数](stastical.md#percentileexc-)     | 特定の範囲に含まれるデータの第 k 百分位数に当たる値を返します (k は 0 より大きく 1 より小さい値)。|
| [PERCENTILEINC 関数](stastical.md#percentileinc-)     | 特定の範囲に含まれるデータの第 k 百分位数に当たる値を返します。|
| [PERCENTRANKEXC 関数](stastical.md#percentrankexc-)   | 配列内での値の順位を百分率 (0 より大きく 1 より小さい) で返します。|
| [PERCENTRANKINC 関数](stastical.md#percentrankinc-)   | 配列内での値の順位を百分率 (0 ～ 1、0 および 1 を含む) で返します。|
| [QUARTILEEXC 関数](stastical.md#quartileexc-)         | 0 ～ 1 の間 (0 および 1 を除く) の百分率の値に基づいて、データの配列の四分位数を返します。|
| [QUARTILEINC 関数](stastical.md#quartileinc-)         | 0 ～ 1 の間 (0 および 1 を含む) の百分率の値に基づいて、データの配列の四分位数を返します。|
| [RANK.AVG 関数](stastical.md#rankavg-)                | 数値のリストの中で、指定した数値の序列を返します。|
| [RANK.EQ 関数](stastical.md#rankeq-)                  | 数値のリストの中で、指定した数値の序列を返します。|
| [SMALL 関数](stastical.md#small-)                     | 指定されたデータの中で、k 番目に小さなデータを返します。 |
| [STDEV.P 関数](stastical.md#stdevp-)                  | 引数を母集団全体と見なし、母集団の標準偏差を返します。|
| [STDEV.S 関数](stastical.md#stdevs-)                  | 引数を正規母集団の標本と見なし、標本に基づいて母集団の標準偏差の推定値を返します。|
| [TRIMMEAN 関数](stastical.md#trimmean-)               | データの中間項の平均を返します。|
| [VAR.P 関数](stastical.md#varp-)                      | 引数を母集団全体と見なし、母集団の分散 (標本分散) を返します。|
| [VAR.S 関数](stastical.md#vars-)                      | 標本に基づいて母集団の分散の推定値 (不偏分散) を返します。|

</div></details>

<details><summary>文字列関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [ASC 関数](text.md#asc-)                              | 文字列内の全角 (2 バイト) の英数カナ文字を半角 (1 バイト) 文字に変換します。|
| [CHAR 関数](text.md#char-)                            | 数値で指定された文字を返します。|
| [CODE 関数](text.md#code-)                            | テキスト文字列内の先頭文字の数値コードを返します。|
| [CONCAT 関数](text.md#concat-)                        | 複数の文字列を結合して 1 つの文字列にまとめます。|
| [CONCATENATE 関数](text.md#concatenate-)              | 複数の文字列を結合して 1 つの文字列にまとめます。|
| [DOLLAR 関数](text.md#dollar-)                        | 数値を四捨五入し、通貨書式を設定した文字列に変換します。|
| [EXACT 関数](text.md#exact-)                          | 2 つの文字列が等しいかどうかを判定します。|
| [FIND 関数](text.md#find-)                            | 指定された文字列を他の文字列の中で検索します。|
| [FIXED 関数](text.md#fixed-)                          | 数値を四捨五入し、書式設定した文字列に変換します。|
| [JIS 関数](text.md#jis-)                              | 文字列内の半角 (1 バイト) の英数カナ文字を全角 (2 バイト) 文字 に変換します。|
| [LEFT 関数](text.md#left-)                            | 文字列の先頭から指定された数の文字を返します。|
| [LEN 関数](text.md#len-)                              | 文字列の文字数を返します。|
| [LOWER 関数](text.md#lower-)                          | 文字列に含まれる英大文字をすべて小文字に変換します。|
| [MID 関数](text.md#mid-)                              | 文字列の指定された位置から指定された文字数の文字を返します。|
| [PROPER 関数](text.md#proper-)                        | 文字列に含まれる英単語の先頭文字だけを大文字に変換します。|
| [REPLACE 関数](text.md#replace-)                      | 文字列中の指定された数の文字を他の文字に置き換えます。|
| [REPT 関数](text.md#rept-)                            | 文字列を指定された回数だけ繰り返して表示します。|
| [RIGHT 関数](text.md#right-)                          | 文字列の末尾 (右端) から指定された文字数の文字を返します。|
| [SEARCH 関数](text.md#search-)                        | 指定された文字列を他の文字列の中で検索します。大文字と小文字は区別されません。|
| [SUBSTITUTE 関数](text.md#substitute-)                | 文字列中の指定された文字を他の文字に置き換えます。|
| [TEXTJOIN 関数](text.md#textjoin-)                    | 複数の範囲や文字列からのテキストを結合し、結合する各テキスト値の間に指定した区切り記号を挿入します。|
| [TRIM 関数](text.md#trim-)                            | 文字列から余分なスペースを削除します。|
| [UPPER 関数](text.md#upper-)                          | 文字列を大文字に変換します。|
| [YEN 関数](text.md#yen-)                              | 数値を四捨五入し、通貨書式を設定した文字列に変換します。|

</div></details>

<details><summary>その他の関数</summary><div>

| 関数                                                                  | 説明              |
|:----------------------------------------------------------------------|:-----------------|
| [UNIQUE 関数](miscellaneous.md#unique-)               | 重複しない値を抽出します。|
| [NULL 関数](miscellaneous.md#null-)                   | NULL を返します。|

</div></details>

<br />

[トップページ](index.md)