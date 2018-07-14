# i-Cart mini

オープンソース移動ロボットプラットフォームi-Cart miniの制作・使用に必要な情報のリポジトリ
Repository for making and operating the open source mobile robot platform i-Cart mini

## パーツリスト (parts list)

T-frogプロジェクト i-Cart mini 部品リスト (Designed By Shigeru Bando 2014/09/14)
[parts_list.csv](parts_list.csv)

リスト中に記載の金額は、参考価格です。入手については各メーカや取扱商社にお問い合わせ下さい。なお、※印については、商社であるヤトロ電子 (www.yatoro.co.jp/) で、2013年6月に見積もりをとった折の価格です。
Prices written in the parts list are for reference surveyed at June 2013.

## YP-Spur パラメータファイル (YP-Spur parameter file)

i-Cart miniは、二軸モータドライバ TF-2MD3-R6と走行制御用プログラムYP-Spurを組み合わせて動作するように設計されています。YP-Spurを使用するためには、ロボットの各種パラメータを記録したパラメータファイルが必要となります。
The i-Cart mini is designed to be controlled by the mobile robot control software YP-Spur. It requires the parameter file that defines robot hardware parameters.

[icart-mini.param](icart-mini.param)
