       Bilingual Emacspeak Platform Windows版インストールの手引き
Copyright (C) 2001 BEP(Bilingual Emacspeak Project)
Author: Mitsugu SAKAMOTO <mitsugu@argv.org>
最終更新日:$Date: 2001/12/26 01:26:38 $

目次
0 はじめに
1 このパッケージについて
2 パッケージの内容
3 インストール
3-1 動作環境
3-2 インストール方法
4 Meadowの起動
5 Q&A
6 参考資料

0 初めに
このドキュメントでは、Bilingual Emacspeak Platform(以下BEPと略す)Windows
版のインストールの方法を説明します。また、Emacs(Meadow)を使う上で参考に
なる資料を紹介します。

1 このパッケージについて
BEPは、視覚障害者がGNU Emacsというテキストエディタを、日英２ヶ国語の音声
出力を利用して使うためのソフトウェアです。
このパッケージは、BEPの初期導入を容易にするために作成しました。
フリーソフトウェアとして配布できる、BEPのWindows版を動作させるためのファ
イルが含まれています。

2 パッケージの内容
パッケージには以下のものが含まれています。
(1) Meadow 1.15pre1一式
Windows版のGNU EmacsであるMeadow本体です。
(2) Windows用スピーチサーバ(Speak.exe)
(3) BEPのプログラム本体

3 インストール
3-1 動作環境
(1) OS: Windows98/Windows98SE/WindowsME/Windows2000SP2
(2) 日本語用音声合成ライブラリ: IBM ProTalker 97
(3) 英語用音声合成ライブラリ: Microsoft Text-to-Speech Engine

3-2 インストール方法
(1)音声合成ライブラリをインストールします。
BEPを動作させるには、日本語と英語の音声合成ライブラリが必要です。
このパッケージには、音声合成ライブラリは含まれていません。各自でインストー
ルする必要があります。

(A)英語用音声合成ライブラリ
英語用音声合成ライブラリには、MicrosoftのText-to-Speechエンジン(英語版)
を、使用することができます。
http://activex.microsoft.com/activex/controls/sapi/spchapi.exe
http://download.microsoft.com/msdownload/sapi/4.0/rtw/4.0a/en/msttsL.EXE
の二つをダウンロードし実行してください。

(B)日本語音声合成ライブラリ
日本語音声合成ライブラリの IBM ProTalker97は、IBMの商品です。(9800円)
Protalker97は、パソコンショップで購入することができます。
もし、、IBMホームページリーダーや、PC-Talker/VDM100W、JAWSなどが
インストールされていれば、必要なものが入っているので、インストールする必
要は在りません。
また、以下のURLから評価きっとをダウンロードすれば、評価用として
ProTalker97を入手することができます。
http://www.jp.ibm.com/voiceland/pt20/

(2)BEPのパッケージを、以下からダウンロードします。
ftp://ftp.m17n.org/BEP/bepw01.exe

(3)ダウンロードしたbepw01.exeをエクスプローラなどで実行します。
実行すると、「BEPの解凍を行います。よろしいですか？」とたずねるダイアログボッ
クスが出るので、[OK]を押してください。
すると、展開先をたずねるダイアログボックスが出るので、良ければ[OK]を押し
てください。
ファイルを展開した後、Meadowを最終組立てして、インストールを終
了します。デフォルトでは、c:\Meadowというフォルダの下にBEPのファイルがイ
ンストールされます。
(注意)
BEPのインストール先を指定する場合は、「C:\」とか、「D:\」などのように、ルート
ディレクトリの直下にするようにしてください。
「C:\Program Files」 のように、サブディレクトリにインストールをすると、
現在では、Meadowが正常に動作しません。

4 Meadowの起動
Meadowは、以下のようにして起動します。

(1) スタートメニューを開きます。
 Windowsキーがあるコンピュータでは、Windowsキーを押します。無いコンピュー
 タでは、 CTRL キーを押しながら、 ESC キーを押します。
(2)上下矢印キーを使って、「プログラム」を選びます。
(3)右矢印キーを押します。
(4)上下矢印キーを使って、「Meadow」を選びます。
(5)右矢印きーを押します。
(6)この中にMeadowへのショートカットのアイコンがあるので、選んでエンターキー
 を押します。
(7)これでMeadowが起動しました。しばらくすると、英語でのアナウンスメッセー
 ジが流れてきます。

5 Q&A

Q1: うまく行きません。
A1: BEPに関しての議論は、BEPメーリングリストで行われています。以下のアドレス
bep-subscribe@argv.org
へ空のメールを送ってください。確認のメールが送られてきますので、指示に従っ
て返信してください。
メーリングリストへの参加の手続きが完了しましたら、使っているOSの種類、何をどこから
ダウンロードしたか、それに対してどんな操作をしたかを書いて質問してみてく
ださい。

Q2: BEPが起動しました。終了のさせ方がわかりません。ALT+F4を押したのです
 が、終了できません。
A2: BEP(Meadow)を終了させるには、CTRLを押しながらxを押してから、CTRLを押
 しながらcを押します。

Q3: Meadowの使い方を覚えたいのですが。
A3: Meadowを起動した後、CTRLを押しながらhを押してから、tを押します。すると、
Meadowのチュートリアルが表示されます。

Q4: しばらく使っているとBEPの音が鳴らなくなるのですが。
A4: 現在のBEPでは、何らかの原因でSpeak.exeから音が出ない状態になることが
あります。
CTRLを押しながらeを押してから、CTRLを押しながらsを押して、Speak.exeを再起動
させてください。

Q5: 音声のスピードを変えたいのですが。
A5: CTRLを押しながらeを押してから、ｄを押して1から9までの数字を入れます。すると、速さが設定され、
(Set speech rate to 160)
のように、設定された数値を音声でアナウンスします。
注意: 数字はお好みに調節してください。数字が大きくなるほど速くなり、小さ
くなるほど遅くなります。

6 参考資料
Meadowや、Emacsの使い方を学ぶのに役に立ちそうな Web を紹介します。

(1) Meadow FAQ
http://faq.meadowy.org/
Meadowについての質問と回答集です。Meadowについてわからないことがあったら、まずここを見
ましょう。

(2) Emacsの遊び方
http://www.argv.org/bep/common/play_with.html
MeadowとBEPを使っての遊び方のページです。

(3) Edit With Emacs
http://webclub.kcom.ne.jp/mb/colo/em_id.html
Emacsの基本的な編集の方法が解説されています。

(4) Emacspeakのページ(英語)
http://emacspeak.sourceforge.net/
BEPの元になった Emacspeak のページです。英語ですが、ユーザーズガイドなど
のマニュアルが読めます。英語が得意な人は、読んでみると参考になるかもしれ
ません。

7. 連絡先
BEPのプログラムに関する質問、バグレポートは、BEPメーリングリストへお願いします。メーリ
ングリストへの参加の方法は、Q1を参照してください。
その他、ご不明な点がありましたら、
bep-contact@argv.org
まで、メールでお問い合わせください。
