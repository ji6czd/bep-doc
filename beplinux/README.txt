Bilingual Emacspeak Platform - Release 20020214(Based on Emacspeak 16.0)
Copyright (C) 1999-2002 Bilingual Emacspeak Project
Documented by: Koichi INOUE <inoue@argv.org>
�ŏI�X�V��:$Date: 2002/05/09 16:09:12 $
$Revision: 1.6 $


�ڎ�

0. �{�p�b�P�[�W�ɂ���
1. Bilingual Emacspeak Platform�Ƃ́H
2. �C���X�g�[��
3. �Q�l����
4. �z�z����
5. �A���擙


0. �{�p�b�P�[�W�ɂ���

�{�p�b�P�[�W��Bilingual Emacspeak Platform(�ȉ�BEP)��Emacs lisp�������z
�z�p�b�P�[�W�ł��BLinux��ł��g�p�ɂȂ�ꍇ�A��������Windows��ɂĊȒP�C
���X�g�[���p�b�P�[�W�����g���Ɂu�Ȃ�Ȃ��v�ꍇ�ɕK�v�ƂȂ�܂��B


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
���p�ɂ�Emacs-20.7�ȍ~�A�y�т�����x�[�X�Ƃ���Meadow(1.15����)���K�v��
���BBEP�̃C���X�g�[���̑O�ɂ������C���X�g�[�����Ă��������B

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

emacspeak-16.0.tar.gz��K���ȏꏊ�ɓW�J���܂��B
���ɁA�{�p�b�P�[�W�Ɋ܂܂��t�@�C�����ׂĂ��A�f�B���N�g���\����ۂ�����
�ԂŁA�W�J����emacspeak-16.0�f�B���N�g�����ɃR�s�[���܂��B�����̃t�@�C��
��������(Makefile�Ȃ�)����܂����㏑�����Ă��������B

�����Bilingual Emacspeak Platform��lisp���z�z�t�@�C������������܂��B


2.3 �C���X�g�[��

emacspeak-16.0�f�B���N�g���ňȉ������s���܂��B
% make config
% make emacspeak

����ɁA�V�X�e���S�̂ŗ��p����ꍇ��root�ɂȂ�A�ȉ��̂悤�ɃC���X�g�[��
���܂��B
# make install

�Ō�ɁAemacspeak-16.0�f�B���N�g�����ɍ쐬����Ă���dot.emacs.add�t�@�C
����.emacs�ɒǉ����܂��B���e�͓K�X�ҏW���Ă��������B

2.4 BEP�̋N��

Emacs���N�����A
M-x load-bemacspeak
�Ɠ��͂���ƋN�����܂��B
�p��ňȉ��̂悤�ȋN�����b�Z�[�W������ׂ����琬���ł��B
�uPress C-h C-e to get an   overview of emacspeak  16.0.
 I am  completely operational,  and all my circuits are
 functioning perfectly!�v

�����̉����Đ��ł�����ł́u�g�b�J�[�^�ƃt�[�K�v�ƁuThis is Emacspeak�v
�Ƃ��������������ɗ���܂��B


3. �Q�l����

Emacs/Meadow��BEP�̎g�������w�Ԃ̂ɖ��ɗ��������� Web ���Љ�܂��B

(1) Meadow FAQ
�@�@http://faq.meadowy.org/

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


4. �z�z����

�{�\�t�g�E�F�A�̔z�z��GNU Emacs�Ɠ������AGPL(GNU General Public License)
��Version 2�܂��͂���ȍ~�ɏ]���܂��B
�ڂ����͓�����COPYING���Q�Ƃ��Ă��������B


5. �A���擙

Bilingual Emacspeak Project�Ɋւ������
http://www.argv.org/bep/
�ɂĐ����X�V���Ă��܂��B
�܂��A�{�\�t�g�E�F�A�Ɋւ��Ă��s���ȓ_�́ABEP���[�����O���X�g�ɓo�^����
���₵�Ă����������A
bep-contact@argv.org
�܂ł��肢���܂��B
