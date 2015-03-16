WS2822S
============
シリアルフルカラーLED WS2822Sを制御するためのライブラリです。
> examples  ----------WS2822Sを使用したサンプルスケッチ
 + LED_bar_10  ------- WS2822Sを10個光らせるサンプルスケッチ
 + addresss_write ------- WS2822Sにアドレスを書き込むサンプルスケッチ
 
> Ws2822s.cpp

> Ws2822s.h

> keywords.txt

*動作確認 Arduino Uno

使い方
=============
初期設定

+ 最初に使用するピンの番号を指定します。
+ サンプルスケッチでは色信号を出すピンを13番、アドレスを書き込むピンを12番としました。
+ 制御するWS2822Sの数を指定します。サンプルスケッチでは10個です。
+ 例:  Ws2822s  LED(13, 12, 10);

アドレス書き込み

+　WS2822Sのアドレスは3ずつ増やす必要があるため、先頭のLEDがアドレス1番なら次は4番、続けて7、10、13、16となります。
+  このライブラリではアドレスの割り当てを単純化して先頭から0、1、2、3、4と割り当てられるようにしてあります。

