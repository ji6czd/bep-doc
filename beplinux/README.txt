Bilingual Emacspeak Platform - Release 02(Based on Emacspeak 15.0)
                              2001/12/29
Copyright (C) 1999-2001 Bilingual Emacspeak Project
Author: Koichi INOUE <inoue@argv.org>
最終更新日:$Date: 2002/02/13 17:51:31 $
$Revision: 1.1 $


目次

0. 本パッケージについて
1. Bilingual Emacspeak Platformとは？
2. インストール/利用方法
3. 配布条件
4. 連絡先等


0. 本パッケージについて

本パッケージはBilingual Emacspeak Platform(以下BEP)のEmacs lisp部配布パッ
ケージです。Linux上でご使用になる場合、もしくはWindows上にて簡単インストー
ルパッケージをお使いに「ならない」場合に必要となります。


1. Bilingual Emacspeak Platformとは？

Bilingual Emacspeak PlatformはT. V. Raman作のEmacs音声化システムである
Emacspeakを日本語が使えるように拡張したもので、以下のような特徴があります。

(1)バイリンガル
バイリンガル: Windows上では、専用のスピーチサーバを利用することで日英二
カ国後をネイティブな発音で読み上げるバイリンガルな音声Emacs環境を実現し
ます。Linux上では現在日本語のみに対応し、英語は読み変え辞書を用いてカタ
カナ英語で読み上げます。Linuxでのバイリンガル化は現在作業中です。

(2)LinuxとWindowsに対応
EmacspeakがサポートするLinuxに加え、MicrosoftWindows上でも利用可能です。
(現状はWindowsの方が安定した利用が可能です。)

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

利用にはEmacs-20.7以降、及びそれをベースとしたMeadow(1.15推奨)が必要で
す。BEPのインストールの前にそれらをインストールしてください。Emacs-21で
も動作しますが、若干の不具合があります。

本パッケージの利用には、お使いのオペレーティングシステム専用のスピーチサー
バを別途入手していただく必要があります。BEPのWEBページ
(http://www.argv.org/bep/)からそれぞれのインストール方法に関するページを
ご覧ください。

Windows版: http://www.argv.org/bep/Windows/
Linux版:   http://www.argv.org/bep/Linux/

また、Linux上でご使用の場合は、本パッケージに付属のREADME.BEP.Linuxファ
イルを参考にしてください。


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
