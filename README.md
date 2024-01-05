# md2csv

md2csv make csv or excel file from some markdown file.

## usage

   1. output csv to stdout

	$ ./md2csv test.md
	# 不具合番号, 概要, 事象, 原因, 対策
	"123", "偽札の品質が悪い", "「いい出来ではないな」<BR>「このところ質が落ちていくばかりではないか」", "「申し訳ございません。しかし、今のような大量生産を続けては・・・。」", "「やり直せ、納期も遅らせてはならん」"

   2. output csv file

	$ ./md2csv -o test.csv test.md
	$ nkf --guess test.csv
	Shift_JIS (CRLF)

   3. output excel file

	$ ./md2csv -o test.xlsx test.md
