Bilingual Emacspeak Platform - Release 20020214(Based on Emacspeak 15.0)
                              2001/12/29
Copyright (C) 1999-2001 Bilingual Emacspeak Project
Documented by: Koichi INOUE <inoue@argv.org>
�ŏI�X�V��:$Date: 2002/02/13 19:01:54 $
$Revision: 1.2 $


�ڎ�

0. �{�p�b�P�[�W�ɂ���
1. Bilingual Emacspeak Platform�Ƃ́H
2. �C���X�g�[��/���p���@
3. �z�z����
4. �A���擙


0. �{�p�b�P�[�W�ɂ���

�{�p�b�P�[�W��Bilingual Emacspeak Platform(�ȉ�BEP)��Emacs lisp�������z
�z�p�b�P�[�W�ł��BLinux��ł��g�p�ɂȂ�ꍇ�A��������Windows��ɂĊȒP�C
���X�g�[���p�b�P�[�W�����g���Ɂu�Ȃ�Ȃ��v�ꍇ�ɕK�v�ƂȂ�܂��B


1. Bilingual Emacspeak Platform�Ƃ́H

Bilingual Emacspeak Platform��T. V. Raman���Emacs�������V�X�e���ł���
Emacspeak����{�ꂪ�g����悤�Ɋg���������̂ŁA�ȉ��̂悤�ȓ���������܂��B

(1)�o�C�����K��
�o�C�����K��: Windows��ł́A��p�̃X�s�[�`�T�[�o�𗘗p���邱�Ƃœ��p��
�J������l�C�e�B�u�Ȕ����œǂݏグ��o�C�����K���ȉ���Emacs����������
�܂��B

(2)Linux��Windows�ɑΉ�
Emacspeak���T�|�[�g����Linux�ɉ����AMicrosoftWindows��ł����p�\�ł��B
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
  �E�u���E�U: Emacs-w3
  �E�����쐬�x����: YaTeX�y��YaHTML
  �E���{����͗p�N���C�A���g: egg V4
  �EIRC�N���C�A���g: liece


2. �C���X�g�[��/���p���@

2.1 �K�v�Ȃ���

�EGNU Emacs
���p�ɂ�Emacs-20.7�ȍ~�A�y�т�����x�[�X�Ƃ���Meadow(1.15����)���K�v��
���BBEP�̃C���X�g�[���̑O�ɂ������C���X�g�[�����Ă��������BEmacs-21��
�����삵�܂����A�኱�̕s�������܂��B

�E�X�s�[�`�T�[�o
�{�p�b�P�[�W�̗��p�ɂ́A���g���̃I�y���[�e�B���O�V�X�e����p�̃X�s�[�`�T�[
�o��ʓr���肵�Ă��������K�v������܂��BBEP��WEB�y�[�W
(http://www.argv.org/bep/)���炻�ꂼ��̃C���X�g�[�����@�Ɋւ���y�[�W��
�������������B

Windows��: http://www.argv.org/bep/Windows/
Linux��:   http://www.argv.org/bep/Linux/

�EEmacspeak�p�b�P�[�W
�{�p�b�P�[�W�ɂ�Emacspeak-15.0����̃p�b�`�݂̂����^����Ă��܂��B
http://emacspeak.sourceforge.net
����emacspeak�̔z�z�p�b�P�[�W����肵�Ă��������B

2.2 �p�b�`�̓K�p

emacspeak-15.0.tar.gz��K���ȏꏊ�ɓW�J���܂��B
����emacspeak-15.0�f�B���N�g���Ɉړ����āA�p�b�`��K�p���܂��B

% cd emacspeak-15.0
% patch -s -p1 < beprel.patch
(beprel.patch�͖{�p�b�P�[�W�Ɋ܂܂�Ă�����̂��w�肵�܂��B)
�����Bilingual Emacspeak Platform��lisp���z�z�t�@�C������������܂��B

2.3 �C���X�g�[��

emacspeak-15.0�f�B���N�g���ňȉ������s���܂��B
% make config
% make emacspeak

����ɁA�V�X�e���S�̂ŗ��p����ꍇ��root�ɂȂ�A�ȉ��̂悤�ɃC���X�g�[��
���܂��B
# make install

�Ō�ɁAemacspeak-15.0�f�B���N�g�����ɍ쐬����Ă���dot.emacs.add�t�@�C
����.emacs�ɒǉ����܂��B���e�͓K�X�ҏW���Ă��������B

2.4 BEP�̋N��

Emacs���N�����A
M-x load-bemacspeak
�Ɠ��͂���ƋN�����܂��B
�p��ŋN�����b�Z�[�W������ׂ����琬���ł��B�����̉����Đ��ł�����ł�
�u�g�b�J�[�^�ƃt�[�K�v������܂��B


3. �z�z����

�{�\�t�g�E�F�A�̔z�z��GNU Emacs�Ɠ������AGPL(GNU General Public License)
��Version 2�܂��͂���ȍ~�ɏ]���܂��B


4. �A���擙

Bilingual Emacspeak Project�Ɋւ������
http://www.argv.org/bep/
�ɂĐ����X�V���Ă��܂��B
�܂��A�{�\�t�g�E�F�A�Ɋւ��Ă��s���ȓ_�́ABEP���[�����O���X�g�ɓo�^����
���₵�Ă����������A
bep-contact@argv.org
�܂ł��肢���܂��B
