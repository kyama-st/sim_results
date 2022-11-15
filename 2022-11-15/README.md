# 2022-11-15 update
##　ファイル構成
- results_10M: champsimからの出力
- results_10M_JSON: champsimからの出力からjson部分を抜き出したファイル
- results_10M_LINE_AVF: ラインごとのAVFを算出。Wr-ratio等は命令数が100M、500Mは入っている。
- results_10M_PAGE_AVF: ページごとのAVFを算出。100Mにはラインでまとまっているのでない。500Mは参考にしていいか不明。 

## results_10Mについて
results_10Mとかはアクセス回数の数え方が間違っていたので参考にならない

## results_100M
results_100Mはアクセス回数は修正後。
results_100M_variationに標準偏差を載せている
reuslts_100M_LINE_AVF/620.omntemp...* は１ページ内のAVFのヒストグラムを表示している

## results_500M
JSONとLINE＿AVFは使ってOK。
page_AVFは中途半端なデータなのでむしすること。


