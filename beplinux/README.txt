Bilingual Emacspeak Platform - Release 20020214(Based on Emacspeak 15.0)
                              2001/12/29
Copyright (C) 1999-2001 Bilingual Emacspeak Project
Documented by: Koichi INOUE <inoue@argv.org>
最終更新日:$Date: 2002/02/13 19:01:54 $
$Revision: 1.2 $


目次

0. 本パッケージについて
1. Bilingual Emacspeak Platformとは？
2. インストール/利用方法
3. 配布条件
4. 連絡先等


0. 本パッケージについて

本パッケージはBilingual Emacspeak Platform(以下BEP)のEmacs lisp部差分配
布パッケージです。Linux上でご使用になる場合、もしくはWindows上にて簡単イ
ンストールパッケージをお使いに「ならない」場合に必要となります。


1. Bilingual Emacspeak Platformとは？

Bilingual Emacspeak PlatformはT. V. Raman作のEmacs音声化システムである
Emacspeakを日本語が使えるように拡張したもので、以下のような特徴があります。

(1)バイリンガル
バイリンガル: Windows上では、専用のスピーチサーバを利用することで日英二
カ国後をネイティブな発音で読み上げるバイリンガルな音声Emacs環境を実現し
ます。

(2)LinuxとWindowsに対応
EmacspeakがサポートするLinuxに加え、MicrosoftWindows上でも利用可能です。
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
  ・ブラウザ: Emacs-w3
  ・文書作成支援環境: YaTeX及びYaHTML
  ・日本語入力用クライアント: egg V4
  ・IRCクライアント: liece


2. インストール/利用方法

2.1 必要なもの

・GNU Emacs
利用にはEmacs-20.7以降、及びそれをベースとしたMeadow(1.15推奨)が必要で
す。BEPのインストールの前にそれらをインストールしてください。Emacs-21で
も動作しますが、若干の不具合があります。

・スピーチサーバ
本パッケージの利用には、お使いのオペレーティングシステム専用のスピーチサー
バを別途入手していただく必要があります。BEPのWEBページ
(http://www.argv.org/bep/)からそれぞれのインストール方法に関するページを
ご覧ください。

Windows版: http://www.argv.org/bep/Windows/
Linux版:   http://www.argv.org/bep/Linux/

・Emacspeakパッケージ
本パッケージにはEmacspeak-15.0からのパッチのみが収録されています。
http://emacspeak.sourceforge.net
からemacspeakの配布パッケージを入手してください。

2.2 パッチの適用

emacspeak-15.0.tar.gzを適当な場所に展開します。
次にemacspeak-15.0ディレクトリに移動して、パッチを適用します。

% cd emacspeak-15.0
% patch -s -p1 < beprel.patch
(beprel.patchは本パッケージに含まれているものを指定します。)
これでBilingual Emacspeak Platformのlisp部配布ファイルが生成されます。

2.3 インストール

emacspeak-15.0ディレクトリで以下を実行します。
% make config
% make emacspeak

さらに、システム全体で利用する場合はrootになり、以下のようにインストール
します。
# make install

最後に、emacspeak-15.0ディレクトリ内に作成されているdot.emacs.addファイ
ルを.emacsに追加します。内容は適宜編集してください。

2.4 BEPの起動

Emacsを起動し、
M-x load-bemacspeak
と入力すると起動します。
英語で起動メッセージをしゃべったら成功です。複数の音を再生できる環境では
「トッカータとフーガ」が流れます。


3. 配布条件

本ソフトウェアの配布はGNU Emacsと同じく、GPL(GNU General Public License)
のVersion 2またはそれ以降に従います。


4. 連絡先等

Bilingual Emacspeak Projectに関する情報は
http://www.argv.org/bep/
にて随時更新しています。
また、本ソフトウェアに関してご不明な点は、BEPメーリングリストに登録して
質問していただくか、
bep-contact@argv.org
までお願いします。
