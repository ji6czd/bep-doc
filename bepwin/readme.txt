Bilingual Emacspeak Platform Windows�ŃC���X�g�[���̎����

Copyright (C) 1999-2001 Bilingual Emacspeak Project
Author: Mitsugu SAKAMOTO <mitsugu@argv.org>
�ŏI�X�V��:$Date: 2001/12/30 02:14:56 $
$Revision: 1.19 $


�ڎ�

0. �͂��߂�
1. ���̃p�b�P�[�W�ɂ���
2. �p�b�P�[�W�̓��e
3. �C���X�g�[��
 3.1 �����
 3.2 �C���X�g�[�����@
4. Meadow�̋N��
5. Q&A
6. �Q�l����
7. ���̑�
8. �A����


0. ���߂�

���̃h�L�������g�ł́ABilingual Emacspeak Platform (�ȉ� BEP �Ɨ���)
Windows �ł̃C���X�g�[���̕��@��������܂��B�܂��AEmacs (Meadow) ���g
����ŎQ�l�ɂȂ鎑�����Љ�܂��B


1. ���̃p�b�P�[�W�ɂ���

BEP�́A���o��Q�҂� GNU Emacs �Ƃ����e�L�X�g�G�f�B�^���A���p�Q�������
�����o�͂𗘗p���Ďg�����߂̃\�t�g�E�F�A�ł��B

���̃p�b�P�[�W�́ABEP �̏���������e�Ղɂ��邽�߂ɍ쐬���܂����B�t���[
�\�t�g�E�F�A�Ƃ��Ĕz�z�ł���ABEP �� Windows �ł𓮍삳���邽�߂̃t�@
�C�����܂܂�Ă��܂��B


2. �p�b�P�[�W�̓��e

�p�b�P�[�W�ɂ͈ȉ��̎O��ނ��܂܂�Ă��܂��B

(1) Meadow 1.15pre1�ꎮ
    Windows �ł� GNU Emacs �ł��� Meadow �{�̂ł��B

(2) Windows �p�X�s�[�`�T�[�o (speak.exe)
    BEP�� �������������邽�߂̃v���O�����ł��B

(3) BEP �̃v���O�����{��
    BEP �𓮂������߂́A Emacs Lisp �v���O�����ł��B


3. �C���X�g�[��

3.1 �����

�ȉ��̊��œ���m�F���s���܂����B

�EOS: Windows98/Windows98SE/WindowsME/Windows2000SP2
�E���{��p�����������C�u����: IBM ProTalker 97
�E�p��p�����������C�u����: Microsoft Text-to-Speech Engine


3.2 �C���X�g�[�����@

�ȉ��� (1), (2), (3) �����̏��Ɏ��s���ĉ������B

(1) �����������C�u�������C���X�g�[�����܂��B

    BEP �𓮍삳����ɂ́A���{��Ɖp��� SAPI (Speech API) �Ή��̉���
    �������C�u�������K�v�ł����A����特���������C�u�����͂��̃p�b�P�[
    �W�Ɋ܂܂�Ă��܂���B�e���ŃC���X�g�[������K�v������܂��B

    [����] SAPI �ɂ́A���낢��ȃo�[�W����������܂��BBEP �́ASAPI �� 
    Version 4 �ł������삵�܂���B�ꕔ�̊��ŁA�X�N���[�����[�_�[�̔�
    �����x���Ȃ�ƌ����悤�ȗ��R�� SAPI �� Version 3 �ɂ��Ă���ꍇ��
    ���ӂ��K�v�ł��B

    a) �p��p�����������C�u����

     �@�p��p�����������C�u�����ɂ́AMicrosoft �̉p��� Text-to-Speech 
       �G���W�����g�p���܂��B�ȉ��̓���_�E�����[�h���Ď��s���ĉ���
       ���B

       spchapi.exe (825KB)
�@�@   http://activex.microsoft.com/activex/controls/sapi/spchapi.exe

       msttsL.exe (7.3MB)
�@�@   http://download.microsoft.com/msdownload/sapi/4.0/rtw/4.0a/en/msttsL.EXE

    b) ���{�ꉹ���������C�u����

       ���{�ꉹ���������C�u������ IBM ProTalker 97 �́AIBM �̏��i 
       (9800�~) �ł��BProtalker 97 �́A�������������̒P�̂̏��i�Ƃ���
       �p�\�R���V���b�v�ōw���ł��܂��B

       IBM �̃z�[���y�[�W���[�_�[��APC-Talker/VDM100W ���邢�� JAWS 
       �Ȃǂ͓����I�� IBM ProTalker 97 ���g�p���Ă��܂��B���������āA
       �����̃\�t�g�E�F�A�����ɃC���X�g�[������Ă���ꍇ�́A���ɉ�
       �����Ȃ��Ă� BEP �͓��삵�܂��B�������A���C�Z���X�̊֌W�� BEP 
       �p�ɂ͕ʓr�P�̔ł� ProtTalker ���w������K�v������܂��B
 
       [����] ���ł� ProTalker �����삵�Ă�����ōX�ɒP�̔ł� 
       ProTalker ���C���X�g�[������ƁA�����̊������������Ȃ�\��
       ������܂��B�s���̓_�� BEP ���[�����O���X�g (���L) �܂ł��₢��
       �킹���������B

(2) BEP�̃p�b�P�[�W���A�ȉ�����_�E�����[�h���܂��B(14.3MB)

�@�@ftp://ftp.m17n.org/pub/bep/win32/release/bepw01.exe

(3) �_�E�����[�h���� bepw01.exe ���G�N�X�v���[���ȂǂŎ��s���܂��B

    ���s����ƁA�uBEP �̉𓀂��s���܂��B��낵���ł����H�v�Ƃ����˂�_
    �C�A���O�{�b�N�X���o��̂ŁA[OK] �������Ă��������B����ƁA�W�J��
    �������˂�_�C�A���O�{�b�N�X���o��̂ŁA�ǂ���� [OK] �������Ă���
    �����B

    �t�@�C����W�J������AMeadow ���C���X�g�[�����āA�C���X�g�[�����
    ���I�����܂��B�f�t�H���g�ł́Ac:\Meadow �Ƃ����f�B���N�g���̉��� 
    BEP �̃t�@�C�����C���X�g�[������܂��B

    [����] BEP �̃C���X�g�[������w�肷��ꍇ�́A�uC:\�v�Ƃ��A�uD:\�v
    �Ȃǂ̂悤�ɁA���[�g�f�B���N�g���̒����ɂ���悤�ɂ��Ă��������B
    �uC:\Program Files�v �̂悤�ɁA�T�u�f�B���N�g���ɃC���X�g�[������
    ��ƁA���݂ł́AMeadow������ɓ��삵�܂���B


4. Meadow �̋N��

�ȉ��̎菇 (1)�`(7) �ɏ]���� Meadow ���N�����܂��B

(1) �X�^�[�g���j���[���J���܂��B
    Windows �L�[������R���s���[�^�ł́AWindows �L�[�������܂��B�����R
    ���s���[�^�ł́A CTRL �L�[�������Ȃ���A ESC �L�[�������܂��B

(2) �㉺���L�[���g���āA�u�v���O�����v��I�т܂��B

(3) �E���L�[�������܂��B

(4) �㉺���L�[���g���āA�uMeadow�v��I�т܂��B

(5) �E���L�[�������܂��B

(6) ���̒��� Meadow �ւ̃V���[�g�J�b�g�̃A�C�R��������̂ŁA�I��ŃG��
    �^�[�L�[�������܂��B

(7) ����� Meadow ���N�����܂����B���΂炭����ƁA�p��ł̃A�i�E���X���b
    �Z�[�W������Ă��܂��B


5. Q&A

Q1: ���܂��s���܂���B
A1: ���ꂾ���ł͓����悤������܂���BBEP �Ɋւ��Ă̋c�_�́ABEP ���[��
    ���O���X�g�ōs���Ă��܂��B�܂��ABEP ���[�����O���X�g�ւ̎Q���̎�
    �������s���Ă��������B�Q������ɂ͈ȉ��̃A�h���X

�@�@bep-subscribe@argv.org

    �֋�̃��[���𑗂��Ă��������B�m�F�̃��[���������Ă��܂��̂ŁA�w
    ���ɏ]���ĕԐM���Ă��������B�@���[�����O���X�g�ւ̎Q���̎葱������
    �����܂�����A�g���Ă��� OS �̎�ށA�����ǂ�����_�E�����[�h�������A
    ����ɑ΂��Ăǂ�ȑ�����������������Ď��₵�Ă݂Ă��������B

Q2: BEP �� Web �y�[�W�͂���܂����H
A2: �͂��Bhttp://www.argv.org/bep/ �������ł��B

Q3: BEP (Meadow) ���N�����܂����B���A�I���̂��������킩��܂���B
    ALT+F4�� �������̂ł����A�I���ł��܂���B
A3: BEP (Meadow) ���I��������ɂ́ACTRL (�R���g���[���L�[) �������Ȃ�
    ��x��ł��A������ CTRL �������Ȃ���c��ł��܂��B

Q4: Meadow �̎g�������o�������̂ł����B
A4: Meadow ���N��������ACTRL �������Ȃ���h��ł��A���ɒP�Ƃ�t��ł���
    ���B����ƁAMeadow �̃`���[�g���A�����\������܂��B

Q5: ���΂炭�g���Ă���� BEP �̉�������Ȃ��Ȃ�̂ł����B
A5: ���݂� BEP �ł́A���炩�̌����ŉ������o�Ȃ���ԂɂȂ邱�Ƃ������
    ���BCTRL �������Ȃ���e��ł��A���� CTRL �������Ȃ���s��łƁA��
    ���v���O�����������ċN�����邱�Ƃ��ł��܂��̂ł������������B

Q6: �����̃X�s�[�h��ς������̂ł����B
A6: CTRL �������Ȃ���e��ł��A���ɒP�Ƃ�d�Ɛ����ꕶ�� (1�`9�̂ǂꂩ) 
    ����͂��܂��B����ƁA�X�s�[�h�����ݒ肳��A"Set speech rate to
    160" �̂悤�ɁA�ݒ肳�ꂽ���l�������ŃA�i�E���X���܂��B�����͂��D
    �݂ɒ��߂��Ă��������B�������傫���Ȃ�قǑ����Ȃ�A�������Ȃ�ق�
    �x���Ȃ�܂��B


6. �Q�l����

Meadow��AEmacs �̎g�������w�Ԃ̂ɖ��ɗ��������� Web ���Љ�܂��B

(1) Meadow FAQ
�@�@http://faq.meadowy.org/

    Meadow �ɂ��Ă̎���Ɖ񓚏W�ł��BMeadow �ɂ��Ă킩��Ȃ����Ƃ�
    ��������A�܂����������܂��傤�B

(2) Emacs �̗V�ѕ�
�@�@http://www.argv.org/bep/common/play_with.html

    Meadow �� BEP ���g���Ă̗V�ѕ��̃y�[�W�ł��B

(3) Edit With Emacs
�@�@http://webclub.kcom.ne.jp/mb/colo/em_id.html

    Emacs �̊�{�I�ȕҏW�̕��@���������Ă��܂��B

(4) Emacspeak �̃y�[�W (�p��)
�@�@http://emacspeak.sourceforge.net/

    BEP�̌��ɂȂ��� Emacspeak �̃y�[�W�ł��B�p��ł����A���[�U�[�Y�K�C
    �h�Ȃǂ̃}�j���A�����ǂ߂܂��B�p�ꂪ���ӂȐl�́A�ǂ�ł݂�ƎQ�l��
    �Ȃ邩������܂���B


7. ���̑�

���̊ȒP�C���X�g�[���p�b�P�[�W�Ɋ܂܂�� Meadow �̖{�̂ƃ\�[�X�R�[�h�́A
�ȉ��̏ꏊ������肷�邱�Ƃ��ł��܂��B

�@�@ftp://ftp.m17n.org/pub/mule/Windows/


8. �A����

BEP �̃v���O�����Ɋւ��鎿��A�o�O���|�[�g�́ABEP ���[�����O���X�g�ւ�
�肢���܂��B���[�����O���X�g�ւ̎Q���̕��@�́A��� Q1 ���Q�Ƃ��Ă�����
���B���̑��A���s���ȓ_������܂�����A

�@�@bep-contact@argv.org

�܂ŁA���[���ł��₢���킹���������B
