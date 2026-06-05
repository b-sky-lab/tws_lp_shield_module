# Tws-Lp-Jis60 Firmware

## 概要
本リポジトリは [tws_lp_jis60](https://github.com/ar-kr/tws_lp_jis60)のファームウェアを提供するものです．

## キーマップ

画像上はデフォルトのキーマップ，下側は`Fn`キー押下時に使えるキーのマップです．
すなわち，`Fn + 1`で`F1`が，`Fn + BS`で`Delete`が打てます．

また，特殊キー略称の意味は以下の通りです．

- `BT_SEL n`: n番目のペアリング済みBluetoothデバイスに接続
    - 何もペアリングしていない番号を選んだ時は，その番号で新規ペアリング受付状態に入ります．
- `BT_CLR`: 現在接続中のBluetooth接続をペアリング削除
- `BT_CLR_ALL`: 保存済みの全てのBluetooth接続をペアリング削除
- `IND_CON`: Bluetooth接続状態をLEDで表示
    - 青: 接続中
    - 黄: ペアリング待ち
    - 赤: 切断
    - ステータスLEDの色の詳細は次を参照してください: https://github.com/caksoylar/zmk-rgbled-widget 
- `IND_BAT`: バッテリ残量をLEDで表示
    - 緑: 30%以上
    - 黄: 30~10%の間
    - 赤: 10%以下
    - ステータスLEDの色の詳細は次を参照してください: https://github.com/caksoylar/zmk-rgbled-widget 


![doc/images/keymap.png]


https://www.keyboard-layout-editor.com/#/gists/35fc311bae26cc121fb2835988d3a9b2