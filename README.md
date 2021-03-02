# BF-011A
sound effect player by DFPlayer Mini an MP3 module

https://youtu.be/n-CQxfKWx2o

電子工作玩具
効果音再生機「ポン出し」

主な機能

- 14 種類の効果音をボタン 1 発で再生できます
- microSD に書き込んだ音源ファイル (MP3) を再生します
- パワーアンプを内蔵し、スピーカー2台を接続してステレオ再生ができます
- 音量調節は、押ボタンとボリュームダイヤルの2段構えです

説明書:

BF-011A_DOC.pdf

https://github.com/botanicfields/BF-011A/blob/master/V02L02/BF-011A_DOC.pdf

# 音源

[WAV フォルダ](https://github.com/botanicfields/BF-011A/tree/master/wav) にサンプルを置きました。

「BGM・ジングル・効果音のフリー素材 OtoLogic (オトロジック) 」のデータを使用しています。

https://otologic.jp/

DFPlayer Mini は、停止状態から再生すると出だしがフェードインになってしまいます。
先頭に無音部分を付加しても改善効果がありません。
MP3 形式を WAV 形式にすることで少し改善しますが、まだまだ不十分に感じます。
WAV に変換した上で先頭に 10ms 以下のごく小さい音を追加しています。
この追加は効果があります。停止状態からの再生では、フェードインを逆手に取ることができます。
再生中にボタンを押して次の効果音を再生した場合にも、気にならない程度になっています。

プリント基板 V02L01 に添付した microSD には、OtoLogic オリジナルの MP3 ファイルが入っています。
上記 WAV フォルダのファイルと差し替えることができます。

# 参考資料

DFPlaerMini(DFR0299) モジュール

DFRobot DFR-0299:

https://www.dfrobot.com/product-1121.html

https://wiki.dfrobot.com/DFPlayer_Mini_SKU_DFR0299

https://github.com/DFRobot/DFRobotDFPlayerMini

Flyrontech FN-M16P:

http://www.flyrontech.com/eproducts/84.html

http://www.flyrontech.com/uploadfile/download/20184121510393726.pdf

https://docs.google.com/document/d/1sbZnzhrAAXFYlKePREef-rD63molaLCEJMT4LRoT2So/edit

https://github.com/rwpalmer/DFPlay

