Google日本語入力用ローマ字テーブル
====


[yuzuemon/google-japanese-input-romaji-table](https://github.com/yuzuemon/google-japanese-input-romaji-table)のdvorakjp-.txtに一部キーマップを追加したものです。


内容
----

*  dvorak-jp.txt - DvorakJP配列用のローマ字テーブル
*  dvorakjp-.txt - DvorakJP-配列用のローマ字テーブル
*  dvorakjp-edited.txt - DvorakJP-配列用のローマ字テーブル（一部キーマップ追加）


使い方
----

Google日本語入力の環境設定ダイアログを開き、ローマ字テーブルのカスタマイズボタンを押して、編集ボタンの「ファイルからインポート」を選び、`dvorak-jp.txt`または`dvorakjp-.txt`または`dvorakjp-edited.txt`を読み込みます。


`dvorakjp-edited.txt`について
----
`dvorakjp-edited.txt`は`dvorakjp-.txt`に次のキーマップを追加したものになります。

    ;h  ←
    ;t  ↓
    ;n  ↑
    ;s  →
    ;-  〜
    ;[  『
    ;]  』

Google IMEでは、`zh`や`zt`で矢印キーに変換できるkeymapがあります。
しかしQWERTY配列における`z`の位置には、Dvorak配列では`;`があります。
このギャップを埋めるために上記のキーマップを追加しました。

`dvorakjp-edited.txt`では、QWERTY配列の感覚のまま矢印キーを入力できるようになります。