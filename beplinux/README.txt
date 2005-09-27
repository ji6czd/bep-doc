Bilingual Emacspeak Platform - Release 04(Based on Emacspeak 16.0)
Copyright (C) 1999-2003 Bilingual Emacspeak Project
Documented by: Koichi INOUE <inoue@argv.org>
最終更新日:$Date: 2005/09/27 16:41:58 $
$Revision: 1.12 $


目次

0. 本パッケージについて
1. Bilingual Emacspeak Platformとは？
2. インストール
3. バイリンガル機能について
4. 参考資料
5. 配布条件
6. 連絡先等


0. 本パッケージについて

本パッケージはBilingual Emacspeak Platform(以下BEP)のEmacs lisp部差分配
布パッケージです。Linux上でご使用になる場合、もしくはWindows上にて簡単イ
ンストールパッケージをお使いに「ならない」場合に必要となります。

なお、本パッケージはbep-rel03パッケージのバグフィックスです。

1. Bilingual Emacspeak Platformとは？

Bilingual Emacspeak PlatformはT. V. Raman作のEmacs音声化システムである
Emacspeakを日本語が使えるように拡張したもので、以下のような特徴があります。

(1)バイリンガル
専用のスピーチサーバを利用することで日英二カ国後をネイティブな発音で読み
上げるバイリンガルな音声Emacs環境を実現します。

(2)LinuxとWindowsに対応
EmacspeakがサポートするLinuxに加え、Microsoft Windows上でも利用可能です。
(Windows上でのご利用には現在若干の制限があります。Windowsでの完全バイリ
ンガル対応は作業中です。)

(3)日本語詳細読み、日本語入力対応
日本語の詳細読み辞書を用いて、漢字の詳細読みを行うことができます。また、
Linux上では日本語変換にEgg V4を利用していただくことで、日本語変換時の詳
細読みをサポートします。これにより、Linuxで利用可能な日本語音声化環境の
一つとして利用できます。

(4)日本でポピュラーなlispパッケージをサポート
以下のlispパッケージに対応して音声で使いやすい環境を提供します。
  ・メール及びNews: Mew(Version 2.x)及びWanderlust
  ・ブラウザ: Emacs-w3m
  ・文書作成支援環境: YaHTML
  ・日本語入力用クライアント: egg V4
  ・IRCクライアント: liece


2. インストール

2.1 必要なもの

・GNU Emacs
利用にはEmacs-20.7以降、あるいはそれをベースとしたMeadow(1.15推奨)が必要
です。BEPのインストールの前にそれらをインストールしてください。

・スピーチサーバ
本パッケージの利用には、お使いのオペレーティングシステム専用のスピーチサー
バを別途入手していただく必要があります。BEPのWEBページ
(http://www.argv.org/bep/)からそれぞれのインストール方法に関するページを
ご覧ください。

Windows版: http://www.argv.org/bep/Windows/
Linux版:   http://www.argv.org/bep/Linux/

・Emacspeakパッケージ
本パッケージにはEmacspeak-16.0に追加する多言語拡張機能と日本語対応モジュー
ルのみが含まれます。
http://emacspeak.sourceforge.net
からemacspeak 16.0の配布パッケージを入手してください。

2.2 変更部分の適用

emacspeak-16.0.tar.gzパッケージと本パッケージを適当な場所に展開します。
/tmp/srcというディレクトリをつくって作業するとすると、以下のようにします。
----
% cd /tmp/src
% tar xzvf パッケージの保存ディレクトリ/emacspeak-16.0.tar.gz
% tar xzvf パッケージの保存ディレクトリ/emacspeak-16.0-bep-rel04.tar.gz
----

次に、本パッケージに含まれるファイルすべてを、ディレクトリ構造を保った状
態で、展開したemacspeak-16.0ディレクトリ内にコピーします。同名のファイル
がいくつか(Makefileなど)ありますが上書きしてください。
----
% cd emacspeak-16.0
% cp -pr ../emacspeak-16.0-bep-rel04/* .
----

これでBilingual Emacspeak Platformのlisp部配布ファイルが生成されます。


2.3 インストール

emacspeak-16.0ディレクトリで以下を実行します。
----
% make config
% make emacspeak
----

さらに、システム全体で利用する場合はrootになり、以下のようにインストール
します。
----
# make install
----

最後に、emacspeak-16.0ディレクトリ内に作成されているdot.emacs.addファイ
ルを.emacsに追加します。内容は適宜編集してください。

注: 上記のようにすると、emacspeakの関連ファイルは/usr/share/emacsなど
/usrを基準とした場所にインストールされます。Emacs本体がほかのディレクト
リ(たとえば/usr/local)を基準とした場所にインストールされている場合など
BEPのインストール先を変更したい場合は、prefix=で指定します。たとえば
/usr/localディレクトリにインストールしたい場合は、make installの代わりに以下のようにします。
----
# make prefix=/usr/local install
----

2.4 BEPの起動

Emacsを起動し、
M-x bep
と入力すると起動します。
英語で以下のような起動メッセージをしゃべったら成功です。
「Press C-h C-e to get an   overview of emacspeak  16.0.
 I am  completely operational,  and all my circuits are
 functioning perfectly!」

複数の音を再生できる環境では「トッカータとフーガ」と「This is Emacspeak」
という音声も同時に流れます。


3. バイリンガル機能について

BEPでは日本語TTSと英語TTSを切り替えながら文章やメッセージを読み上げるこ
とができます。

3.1 バイリンガルモード

現在、以下の三つのバイリンガルモードが用意されています。

  (1)Native English Mode
  半角英数記号はすべて英語TTSで、それ以外はすべて日本語TTSで読み上げるモー
  ドです。英語を扱うことが種目的な場合、半角と全角の英数記号をはっきり区
  別したい場合に利用します。

  (2) Adaptive English Mode
  まとまった量の英数字は英語TTSで、それ以外は日本語TTSで読み上げるモード
  です。短い英数字は日本語の一部としてカタカナ読みされます。
  日本語が主な文章をなめらかに聞きたい場合に利用します。デフォルトはこの
  モードになっています。

  (3) Katakana English Mode
  可能な限り日本語TTSで読み上げるモードです。
  プログラムの編集など、バイリンガルであることより確実に聞き取れることを
  優先したい場合に利用します。

3.2 バイリンガルモードの切り替え

BEPでは三つのバイリンガルモードを切り替えるために以下のコマンドを追加
しています。

    M-x emacspeak-m17n-ja-change-strategy
    キー: C-e x m s

C-e x m sと入力すると、バイリンガルモードを選ぶための質問が表示されます。
Nativeならn、Adaptiveならa、Katakanaならkを入力すると、バイリンガルモー
ドが切り替わり、「Use Katakana English Mode locally」のように発声します。
(これはkを押した場合です。)

locallyという言葉が示すように、上のコマンドで切り替わるのはその時にアク
ティブなバッファのバイリンガルモードです。もしすべてのバッファのデフォル
トとEmacsが出すメッセージも含めて切り替えたい場合は最初にC-uをつけます。
つまり、C-u C-e x m sとします。
そして選びたいモードの文字を入力すると、「Use Katakana English Mode」の
ように発声して切り替わります。

.emacsで指定する場合は、以下のようにしてください。

    (emacspeak-m17n-ja-change-strategy ?k t)

上記はKatakana English Modeをデフォルトにする記述です。第１引数には対応
する文字の前に?をつけて、「?n」「?a」「?k」のように指定します。
デフォルト値を変更するために、第２引数は必ずtを指定してください。
また、上記の記述はBEPがロードされた後に動作するように記述してください。


4. 参考資料

Emacs/MeadowとBEPの使い方を学ぶのに役に立ちそうな Web を紹介します。

(1) Meadow FAQ
　　http://meadow-faq.sourceforge.net/

    Meadow についての質問と回答集です。Meadow についてわからないことが
    あったら、まずここを見ましょう。

(2) Emacs の遊び方
　　http://www.argv.org/bep/common/play_with.html

    EmacsとBEP を動かしてみて、それだけでできることを解説したページです。

(3) Edit With Emacs
　　http://webclub.kcom.ne.jp/mb/colo/em_id.html

    Emacs の基本的な編集の方法が解説されています。

(4) Emacspeak のページ (英語)
　　http://emacspeak.sourceforge.net/

    BEPの元になった Emacspeak のページです。英語ですが、ユーザーズガイ
    ドなどのマニュアルが読めます。英語が得意な人は、読んでみると参考に
    なるかもしれません。


5. 配布条件

本ソフトウェアの配布はGNU Emacsと同じく、GPL(GNU General Public License)
のVersion 2またはそれ以降に従います。
詳しくは同梱のCOPYINGを参照してください。


6. 連絡先等

Bilingual Emacspeak Projectに関する情報は
http://www.argv.org/bep/
にて随時更新しています。
また、本ソフトウェアに関してご不明な点は、BEPメーリングリストに登録して
質問していただくか、
bep-contact@argv.org
までお願いします。
