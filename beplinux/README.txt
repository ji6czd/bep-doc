Bilingual Emacspeak Platform - Release 04(Based on Emacspeak 16.0)
Copyright (C) 1999-2003 Bilingual Emacspeak Project
Documented by: Koichi INOUE <inoue@argv.org>
�ŏI�X�V��:$Date: 2005/09/27 16:41:58 $
$Revision: 1.12 $


�ڎ�

0. �{�p�b�P�[�W�ɂ���
1. Bilingual Emacspeak Platform�Ƃ́H
2. �C���X�g�[��
3. �o�C�����K���@�\�ɂ���
4. �Q�l����
5. �z�z����
6. �A���擙


0. �{�p�b�P�[�W�ɂ���

�{�p�b�P�[�W��Bilingual Emacspeak Platform(�ȉ�BEP)��Emacs lisp�������z
�z�p�b�P�[�W�ł��BLinux��ł��g�p�ɂȂ�ꍇ�A��������Windows��ɂĊȒP�C
���X�g�[���p�b�P�[�W�����g���Ɂu�Ȃ�Ȃ��v�ꍇ�ɕK�v�ƂȂ�܂��B

�Ȃ��A�{�p�b�P�[�W��bep-rel03�p�b�P�[�W�̃o�O�t�B�b�N�X�ł��B

1. Bilingual Emacspeak Platform�Ƃ́H

Bilingual Emacspeak Platform��T. V. Raman���Emacs�������V�X�e���ł���
Emacspeak����{�ꂪ�g����悤�Ɋg���������̂ŁA�ȉ��̂悤�ȓ���������܂��B

(1)�o�C�����K��
��p�̃X�s�[�`�T�[�o�𗘗p���邱�Ƃœ��p��J������l�C�e�B�u�Ȕ����œǂ�
�グ��o�C�����K���ȉ���Emacs�����������܂��B

(2)Linux��Windows�ɑΉ�
Emacspeak���T�|�[�g����Linux�ɉ����AMicrosoft Windows��ł����p�\�ł��B
(Windows��ł̂����p�ɂ͌��ݎ኱�̐���������܂��BWindows�ł̊��S�o�C��
���K���Ή��͍�ƒ��ł��B)

(3)���{��ڍדǂ݁A���{����͑Ή�
���{��̏ڍדǂݎ�����p���āA�����̏ڍדǂ݂��s�����Ƃ��ł��܂��B�܂��A
Linux��ł͓��{��ϊ���Egg V4�𗘗p���Ă����������ƂŁA���{��ϊ����̏�
�דǂ݂��T�|�[�g���܂��B����ɂ��ALinux�ŗ��p�\�ȓ��{�ꉹ��������
��Ƃ��ė��p�ł��܂��B

(4)���{�Ń|�s�����[��lisp�p�b�P�[�W���T�|�[�g
�ȉ���lisp�p�b�P�[�W�ɑΉ����ĉ����Ŏg���₷������񋟂��܂��B
  �E���[���y��News: Mew(Version 2.x)�y��Wanderlust
  �E�u���E�U: Emacs-w3m
  �E�����쐬�x����: YaHTML
  �E���{����͗p�N���C�A���g: egg V4
  �EIRC�N���C�A���g: liece


2. �C���X�g�[��

2.1 �K�v�Ȃ���

�EGNU Emacs
���p�ɂ�Emacs-20.7�ȍ~�A���邢�͂�����x�[�X�Ƃ���Meadow(1.15����)���K�v
�ł��BBEP�̃C���X�g�[���̑O�ɂ������C���X�g�[�����Ă��������B

�E�X�s�[�`�T�[�o
�{�p�b�P�[�W�̗��p�ɂ́A���g���̃I�y���[�e�B���O�V�X�e����p�̃X�s�[�`�T�[
�o��ʓr���肵�Ă��������K�v������܂��BBEP��WEB�y�[�W
(http://www.argv.org/bep/)���炻�ꂼ��̃C���X�g�[�����@�Ɋւ���y�[�W��
�������������B

Windows��: http://www.argv.org/bep/Windows/
Linux��:   http://www.argv.org/bep/Linux/

�EEmacspeak�p�b�P�[�W
�{�p�b�P�[�W�ɂ�Emacspeak-16.0�ɒǉ����鑽����g���@�\�Ɠ��{��Ή����W���[
���݂̂��܂܂�܂��B
http://emacspeak.sourceforge.net
����emacspeak 16.0�̔z�z�p�b�P�[�W����肵�Ă��������B

2.2 �ύX�����̓K�p

emacspeak-16.0.tar.gz�p�b�P�[�W�Ɩ{�p�b�P�[�W��K���ȏꏊ�ɓW�J���܂��B
/tmp/src�Ƃ����f�B���N�g���������č�Ƃ���Ƃ���ƁA�ȉ��̂悤�ɂ��܂��B
----
% cd /tmp/src
% tar xzvf �p�b�P�[�W�̕ۑ��f�B���N�g��/emacspeak-16.0.tar.gz
% tar xzvf �p�b�P�[�W�̕ۑ��f�B���N�g��/emacspeak-16.0-bep-rel04.tar.gz
----

���ɁA�{�p�b�P�[�W�Ɋ܂܂��t�@�C�����ׂĂ��A�f�B���N�g���\����ۂ�����
�ԂŁA�W�J����emacspeak-16.0�f�B���N�g�����ɃR�s�[���܂��B�����̃t�@�C��
��������(Makefile�Ȃ�)����܂����㏑�����Ă��������B
----
% cd emacspeak-16.0
% cp -pr ../emacspeak-16.0-bep-rel04/* .
----

�����Bilingual Emacspeak Platform��lisp���z�z�t�@�C������������܂��B


2.3 �C���X�g�[��

emacspeak-16.0�f�B���N�g���ňȉ������s���܂��B
----
% make config
% make emacspeak
----

����ɁA�V�X�e���S�̂ŗ��p����ꍇ��root�ɂȂ�A�ȉ��̂悤�ɃC���X�g�[��
���܂��B
----
# make install
----

�Ō�ɁAemacspeak-16.0�f�B���N�g�����ɍ쐬����Ă���dot.emacs.add�t�@�C
����.emacs�ɒǉ����܂��B���e�͓K�X�ҏW���Ă��������B

��: ��L�̂悤�ɂ���ƁAemacspeak�̊֘A�t�@�C����/usr/share/emacs�Ȃ�
/usr����Ƃ����ꏊ�ɃC���X�g�[������܂��BEmacs�{�̂��ق��̃f�B���N�g
��(���Ƃ���/usr/local)����Ƃ����ꏊ�ɃC���X�g�[������Ă���ꍇ�Ȃ�
BEP�̃C���X�g�[�����ύX�������ꍇ�́Aprefix=�Ŏw�肵�܂��B���Ƃ���
/usr/local�f�B���N�g���ɃC���X�g�[���������ꍇ�́Amake install�̑���Ɉȉ��̂悤�ɂ��܂��B
----
# make prefix=/usr/local install
----

2.4 BEP�̋N��

Emacs���N�����A
M-x bep
�Ɠ��͂���ƋN�����܂��B
�p��ňȉ��̂悤�ȋN�����b�Z�[�W������ׂ����琬���ł��B
�uPress C-h C-e to get an   overview of emacspeak  16.0.
 I am  completely operational,  and all my circuits are
 functioning perfectly!�v

�����̉����Đ��ł�����ł́u�g�b�J�[�^�ƃt�[�K�v�ƁuThis is Emacspeak�v
�Ƃ��������������ɗ���܂��B


3. �o�C�����K���@�\�ɂ���

BEP�ł͓��{��TTS�Ɖp��TTS��؂�ւ��Ȃ��當�͂⃁�b�Z�[�W��ǂݏグ�邱
�Ƃ��ł��܂��B

3.1 �o�C�����K�����[�h

���݁A�ȉ��̎O�̃o�C�����K�����[�h���p�ӂ���Ă��܂��B

  (1)Native English Mode
  ���p�p���L���͂��ׂĉp��TTS�ŁA����ȊO�͂��ׂē��{��TTS�œǂݏグ�郂�[
  �h�ł��B�p����������Ƃ���ړI�ȏꍇ�A���p�ƑS�p�̉p���L�����͂������
  �ʂ������ꍇ�ɗ��p���܂��B

  (2) Adaptive English Mode
  �܂Ƃ܂����ʂ̉p�����͉p��TTS�ŁA����ȊO�͓��{��TTS�œǂݏグ�郂�[�h
  �ł��B�Z���p�����͓��{��̈ꕔ�Ƃ��ăJ�^�J�i�ǂ݂���܂��B
  ���{�ꂪ��ȕ��͂��Ȃ߂炩�ɕ��������ꍇ�ɗ��p���܂��B�f�t�H���g�͂���
  ���[�h�ɂȂ��Ă��܂��B

  (3) Katakana English Mode
  �\�Ȍ�����{��TTS�œǂݏグ�郂�[�h�ł��B
  �v���O�����̕ҏW�ȂǁA�o�C�����K���ł��邱�Ƃ��m���ɕ������邱�Ƃ�
  �D�悵�����ꍇ�ɗ��p���܂��B

3.2 �o�C�����K�����[�h�̐؂�ւ�

BEP�ł͎O�̃o�C�����K�����[�h��؂�ւ��邽�߂Ɉȉ��̃R�}���h��ǉ�
���Ă��܂��B

    M-x emacspeak-m17n-ja-change-strategy
    �L�[: C-e x m s

C-e x m s�Ɠ��͂���ƁA�o�C�����K�����[�h��I�Ԃ��߂̎��₪�\������܂��B
Native�Ȃ�n�AAdaptive�Ȃ�a�AKatakana�Ȃ�k����͂���ƁA�o�C�����K�����[
�h���؂�ւ��A�uUse Katakana English Mode locally�v�̂悤�ɔ������܂��B
(�����k���������ꍇ�ł��B)

locally�Ƃ������t�������悤�ɁA��̃R�}���h�Ő؂�ւ��̂͂��̎��ɃA�N
�e�B�u�ȃo�b�t�@�̃o�C�����K�����[�h�ł��B�������ׂẴo�b�t�@�̃f�t�H��
�g��Emacs���o�����b�Z�[�W���܂߂Đ؂�ւ������ꍇ�͍ŏ���C-u�����܂��B
�܂�AC-u C-e x m s�Ƃ��܂��B
�����đI�т������[�h�̕�������͂���ƁA�uUse Katakana English Mode�v��
�悤�ɔ������Đ؂�ւ��܂��B

.emacs�Ŏw�肷��ꍇ�́A�ȉ��̂悤�ɂ��Ă��������B

    (emacspeak-m17n-ja-change-strategy ?k t)

��L��Katakana English Mode���f�t�H���g�ɂ���L�q�ł��B��P�����ɂ͑Ή�
���镶���̑O��?�����āA�u?n�v�u?a�v�u?k�v�̂悤�Ɏw�肵�܂��B
�f�t�H���g�l��ύX���邽�߂ɁA��Q�����͕K��t���w�肵�Ă��������B
�܂��A��L�̋L�q��BEP�����[�h���ꂽ��ɓ��삷��悤�ɋL�q���Ă��������B


4. �Q�l����

Emacs/Meadow��BEP�̎g�������w�Ԃ̂ɖ��ɗ��������� Web ���Љ�܂��B

(1) Meadow FAQ
�@�@http://meadow-faq.sourceforge.net/

    Meadow �ɂ��Ă̎���Ɖ񓚏W�ł��BMeadow �ɂ��Ă킩��Ȃ����Ƃ�
    ��������A�܂����������܂��傤�B

(2) Emacs �̗V�ѕ�
�@�@http://www.argv.org/bep/common/play_with.html

    Emacs��BEP �𓮂����Ă݂āA���ꂾ���łł��邱�Ƃ���������y�[�W�ł��B

(3) Edit With Emacs
�@�@http://webclub.kcom.ne.jp/mb/colo/em_id.html

    Emacs �̊�{�I�ȕҏW�̕��@���������Ă��܂��B

(4) Emacspeak �̃y�[�W (�p��)
�@�@http://emacspeak.sourceforge.net/

    BEP�̌��ɂȂ��� Emacspeak �̃y�[�W�ł��B�p��ł����A���[�U�[�Y�K�C
    �h�Ȃǂ̃}�j���A�����ǂ߂܂��B�p�ꂪ���ӂȐl�́A�ǂ�ł݂�ƎQ�l��
    �Ȃ邩������܂���B


5. �z�z����

�{�\�t�g�E�F�A�̔z�z��GNU Emacs�Ɠ������AGPL(GNU General Public License)
��Version 2�܂��͂���ȍ~�ɏ]���܂��B
�ڂ����͓�����COPYING���Q�Ƃ��Ă��������B


6. �A���擙

Bilingual Emacspeak Project�Ɋւ������
http://www.argv.org/bep/
�ɂĐ����X�V���Ă��܂��B
�܂��A�{�\�t�g�E�F�A�Ɋւ��Ă��s���ȓ_�́ABEP���[�����O���X�g�ɓo�^����
���₵�Ă����������A
bep-contact@argv.org
�܂ł��肢���܂��B
