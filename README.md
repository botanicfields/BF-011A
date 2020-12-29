# BF-011A
sound effect player by DFPlayer Mini an MP3 module

https://youtu.be/avOGrIDkbF8

電子工作玩具
効果音再生機「ポン出し」

主な機能

-	14種類の効果音を押ボタンで再生できます
- microSDに書き込んだ音源ファイル(MP3)を再生します
- パワーアンプを内蔵し、スピーカー2台を接続してステレオ再生ができます
- 音量調節は、押ボタンとボリュームダイヤルの2段構えです

説明書:

BF-011A_DOC.pdf

https://github.com/botanicfields/BF-011A/blob/master/BF-011A_DOC.pdf

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

プリント基板 V02L01 に添付した microSD には、OtoLogic オリジナルの MP3 ファイルを入れています。
上記 WAV フォルダのファイルと差し替えていただくことができます。
