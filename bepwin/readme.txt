Bilingual Emacspeak Platform Windows$BHG%$%s%9%H!<%k$N<j0z$-(B

Copyright (C) 1999-2001 Bilingual Emacspeak Project
Author: Mitsugu SAKAMOTO <mitsugu@argv.org>
$B:G=*99?7F|(B:$Date: 2002/01/05 22:39:14 $
$Revision: 1.20 $


$BL\<!(B

0. $B$O$8$a$K(B
1. $B$3$N%Q%C%1!<%8$K$D$$$F(B
2. $B%Q%C%1!<%8$NFbMF(B
3. $B%$%s%9%H!<%k(B
 3.1 $BF0:n4D6-(B
 3.2 $B%$%s%9%H!<%kJ}K!(B
4. Meadow$B$N5/F0(B
5. Q&A
6. $B;29M;qNA(B
7. $B$=$NB>(B
8. $BO"Mm@h(B


0. $B=i$a$K(B

$B$3$N%I%-%e%a%s%H$G$O!"(BBilingual Emacspeak Platform ($B0J2<(B BEP $B$HN,$9(B)
Windows $BHG$N%$%s%9%H!<%k$NJ}K!$r@bL@$7$^$9!#$^$?!"(BEmacs (Meadow) $B$r;H(B
$B$&>e$G;29M$K$J$k;qNA$r>R2p$7$^$9!#(B


1. $B$3$N%Q%C%1!<%8$K$D$$$F(B

BEP$B$O!";k3P>c32<T$,(B GNU Emacs $B$H$$$&%F%-%9%H%(%G%#%?$r!"F|1Q#2%v9q8l$N(B
$B2;@<=PNO$rMxMQ$7$F;H$&$?$a$N%=%U%H%&%'%"$G$9!#(B

$B$3$N%Q%C%1!<%8$O!"(BBEP $B$N=i4|F3F~$rMF0W$K$9$k$?$a$K:n@.$7$^$7$?!#%U%j!<(B
$B%=%U%H%&%'%"$H$7$FG[I[$G$-$k!"(BBEP $B$N(B Windows $BHG$rF0:n$5$;$k$?$a$N%U%!(B
$B%$%k$,4^$^$l$F$$$^$9!#(B


2. $B%Q%C%1!<%8$NFbMF(B

$B%Q%C%1!<%8$K$O0J2<$N;0<oN`$,4^$^$l$F$$$^$9!#(B

(1) Meadow 1.15pre1$B0l<0(B
    Windows $BHG$N(B GNU Emacs $B$G$"$k(B Meadow $BK\BN$G$9!#(B

(2) Windows $BMQ%9%T!<%A%5!<%P(B (speak.exe)
    BEP$B$N(B $B2;@<$r9g@.$9$k$?$a$N%W%m%0%i%`$G$9!#(B

(3) BEP $B$N%W%m%0%i%`K\BN(B
    BEP $B$rF0$+$9$?$a$N!"(B Emacs Lisp $B%W%m%0%i%`$G$9!#(B


3. $B%$%s%9%H!<%k(B

3.1 $BF0:n4D6-(B

$B0J2<$N4D6-$GF0:n3NG'$r9T$$$^$7$?!#(B

$B!&(BOS: Windows98/Windows98SE/WindowsME/Windows2000SP2
$B!&F|K\8lMQ2;@<9g@.%i%$%V%i%j(B: IBM ProTalker 97
$B!&1Q8lMQ2;@<9g@.%i%$%V%i%j(B: Microsoft Text-to-Speech Engine


3.2 $B%$%s%9%H!<%kJ}K!(B

$B0J2<$N(B (1), (2), (3) $B$r$3$N=g$K<B9T$7$F2<$5$$!#(B

(1) $B2;@<9g@.%i%$%V%i%j$r%$%s%9%H!<%k$7$^$9!#(B

    BEP $B$rF0:n$5$;$k$K$O!"F|K\8l$H1Q8l$N(B SAPI (Speech API) $BBP1~$N2;@<(B
    $B9g@.%i%$%V%i%j$,I,MW$G$9$,!"$=$l$i2;@<9g@.%i%$%V%i%j$O$3$N%Q%C%1!<(B
    $B%8$K4^$^$l$F$$$^$;$s!#3F<+$G%$%s%9%H!<%k$9$kI,MW$,$"$j$^$9!#(B

    [$BCm0U(B] SAPI $B$K$O!"$$$m$$$m$J%P!<%8%g%s$,$"$j$^$9!#(BBEP $B$O!"(BSAPI $B$N(B 
    Version 4 $B$G$7$+F0:n$7$^$;$s!#0lIt$N4D6-$G!"%9%/%j!<%s%j!<%@!<$NH?(B
    $B1~$,CY$/$J$k$H8@$&$h$&$JM}M3$G(B SAPI $B$r(B Version 3 $B$K$7$F$$$k>l9g$O(B
    $BCm0U$,I,MW$G$9!#(B

    a) $B1Q8lMQ2;@<9g@.%i%$%V%i%j(B

     $B!!1Q8lMQ2;@<9g@.%i%$%V%i%j$K$O!"(BMicrosoft $B$N1Q8lHG(B Text-to-Speech 
       $B%(%s%8%s$r;HMQ$7$^$9!#0J2<$NFs$D$r%@%&%s%m!<%I$7$F<B9T$7$F2<$5(B
       $B$$!#(B

       spchapi.exe (825KB)
$B!!!!(B   http://activex.microsoft.com/activex/controls/sapi/spchapi.exe

       msttsL.exe (7.3MB)
$B!!!!(B   http://download.microsoft.com/msdownload/sapi/4.0/rtw/4.0a/en/msttsL.EXE

    b) $BF|K\8l2;@<9g@.%i%$%V%i%j(B

       $BF|K\8l2;@<9g@.%i%$%V%i%j$N(B IBM ProTalker 97 $B$O!"(BIBM $B$N>&IJ(B 
       (9800$B1_(B) $B$G$9!#(BProtalker 97 $B$O!"2;@<9g@.$@$1$NC1BN$N>&IJ$H$7$F(B
       $B%Q%=%3%s%7%g%C%W$G9XF~$G$-$^$9!#(B

       IBM $B$N%[!<%`%Z!<%8%j!<%@!<$d!"(BPC-Talker/VDM100W $B$"$k$$$O(B JAWS 
       $B$J$I$OFbItE*$K(B IBM ProTalker 97 $B$r;HMQ$7$F$$$^$9!#$7$?$,$C$F!"(B
       $B$3$l$i$N%=%U%H%&%'%"$,4{$K%$%s%9%H!<%k$5$l$F$$$k>l9g$O!"FC$K2?(B
       $B$b$7$J$/$F$b(B BEP $B$OF0:n$7$^$9!#$?$@$7!"%i%$%;%s%9$N4X78>e(B BEP 
       $BMQ$K$OJLESC1BNHG$N(B ProtTalker $B$r9XF~$9$kI,MW$,$"$j$^$9!#(B
 
       [$BCm0U(B] $B$9$G$K(B ProTalker $B$,F0:n$7$F$$$k4D6-$G99$KC1BNHG$N(B 
       ProTalker $B$r%$%s%9%H!<%k$9$k$H!"4{B8$N4D6-$,$*$+$7$/$J$k2DG=@-(B
       $B$,$"$j$^$9!#ITL@$NE@$O(B BEP $B%a!<%j%s%0%j%9%H(B ($B2<5-(B) $B$^$G$*Ld$$9g(B
       $B$o$;$/$@$5$$!#(B

(2) BEP$B$N%Q%C%1!<%8$r!"0J2<$+$i%@%&%s%m!<%I$7$^$9!#(B(14.3MB)

$B!!!!(Bftp://ftp.m17n.org/pub/bep/win32/release/bepw01.exe

(3) $B%@%&%s%m!<%I$7$?(B bepw01.exe $B$r%(%/%9%W%m!<%i$J$I$G<B9T$7$^$9!#(B

    $B<B9T$9$k$H!"!V(BBEP $B$N%$%s%9%H!<%k$r9T$$$^$9!#$h$m$7$$$G$9$+!)!W$H$?$:$M$k%@(B
    $B%$%"%m%0%\%C%/%9$,=P$k$N$G!"(B[OK] $B$r2!$7$F$/$@$5$$!#$9$k$H!"%$%s%9%H!<%k@h(B
    $B$r$?$:$M$k%@%$%"%m%0%\%C%/%9$,=P$k$N$G!"NI$1$l$P(B [OK] $B$r2!$7$F$/$@(B
    $B$5$$!#(B

    $B%U%!%$%k$rE83+$7$?8e!"(BMeadow $B$r%$%s%9%H!<%k$7$F!"%$%s%9%H!<%k:n6H(B
    $B$r=*N;$7$^$9!#%G%U%)%k%H$G$O!"(Bc:\Meadow $B$H$$$&%G%#%l%/%H%j$N2<$K(B 
    BEP $B$N%U%!%$%k$,%$%s%9%H!<%k$5$l$^$9!#(B

    [$BCm0U(B] BEP $B$N%$%s%9%H!<%k@h$r;XDj$9$k>l9g$O!"!V(BC:\Program Files$B!W(B $B$N(B
    $B$h$&$K!"%9%Z!<%9$,4^$^$l$k%G%#%l%/%H%j$O;XDj$7$J$$$G$/$@$5$$!#$=$N$h(B
    $B$&$J%G%#%l%/%H%j$K%$%s%9%H!<%k$r$9$k$H!"8=:_$G$O!"(BMeadow$B$,@5>o$KF0:n$7$^$;$s!#(B


4. Meadow $B$N5/F0(B

$B0J2<$N<j=g(B (1)$B!A(B(7) $B$K=>$C$F(B Meadow $B$r5/F0$7$^$9!#(B

(1) $B%9%?!<%H%a%K%e!<$r3+$-$^$9!#(B
    Windows $B%-!<$,$"$k%3%s%T%e!<%?$G$O!"(BWindows $B%-!<$r2!$7$^$9!#L5$$%3(B
    $B%s%T%e!<%?$G$O!"(B CTRL $B%-!<$r2!$7$J$,$i!"(B ESC $B%-!<$r2!$7$^$9!#(B

(2) $B>e2<Lp0u%-!<$r;H$C$F!"!V%W%m%0%i%`!W$rA*$S$^$9!#(B

(3) $B1&Lp0u%-!<$r2!$7$^$9!#(B

(4) $B>e2<Lp0u%-!<$r;H$C$F!"!V(BMeadow$B!W$rA*$S$^$9!#(B

(5) $B1&Lp0u%-!<$r2!$7$^$9!#(B

(6) $B$3$NCf$K(B Meadow $B$X$N%7%g!<%H%+%C%H$N%"%$%3%s$,$"$k$N$G!"A*$s$G%(%s(B
    $B%?!<%-!<$r2!$7$^$9!#(B

(7) $B$3$l$G(B Meadow $B$,5/F0$7$^$7$?!#$7$P$i$/$9$k$H!"1Q8l$G$N%"%J%&%s%9%a%C(B
    $B%;!<%8$,N.$l$F$-$^$9!#(B


5. Q&A

Q1: $B$&$^$/9T$-$^$;$s!#(B
A1: $B$3$l$@$1$G$OEz$($h$&$,$"$j$^$;$s!#(BBEP $B$K4X$7$F$N5DO@$O!"(BBEP $B%a!<%j(B
    $B%s%0%j%9%H$G9T$o$l$F$$$^$9!#$^$:!"(BBEP $B%a!<%j%s%0%j%9%H$X$N;22C$N<j(B
    $BB3$-$r9T$C$F$/$@$5$$!#;22C$9$k$K$O0J2<$N%"%I%l%9(B

$B!!!!(Bbep-subscribe@argv.org

    $B$X6u$N%a!<%k$rAw$C$F$/$@$5$$!#3NG'$N%a!<%k$,Aw$i$l$F$-$^$9$N$G!";X(B
    $B<($K=>$C$FJV?.$7$F$/$@$5$$!#!!%a!<%j%s%0%j%9%H$X$N;22C$N<jB3$-$,40(B
    $BN;$7$^$7$?$i!";H$C$F$$$k(B OS $B$N<oN`!"2?$r$I$3$+$i%@%&%s%m!<%I$7$?$+!"(B
    $B$=$l$KBP$7$F$I$s$JA`:n$r$7$?$+$r=q$$$F<ALd$7$F$_$F$/$@$5$$!#(B

Q2: BEP $B$N(B Web $B%Z!<%8$O$"$j$^$9$+!)(B
A2: $B$O$$!#(Bhttp://www.argv.org/bep/ $B$,$=$&$G$9!#(B

Q3: BEP (Meadow) $B$,5/F0$7$^$7$?!#$,!"=*N;$N$5$;J}$,$o$+$j$^$;$s!#(B
    ALT+F4$B$r(B $B2!$7$?$N$G$9$,!"=*N;$G$-$^$;$s!#(B
A3: BEP (Meadow) $B$r=*N;$5$;$k$K$O!"(BCTRL ($B%3%s%H%m!<%k%-!<(B) $B$r2!$7$J$,(B
    $B$i(Bx$B$rBG$A!"B3$$$F(B CTRL $B$r2!$7$J$,$i(Bc$B$rBG$A$^$9!#(B

Q4: Meadow $B$N;H$$J}$r3P$($?$$$N$G$9$,!#(B
A4: Meadow $B$r5/F0$7$?8e!"(BCTRL $B$r2!$7$J$,$i(Bh$B$rBG$A!"<!$KC1FH$N(Bt$B$rBG$A$^(B
    $B$9!#$9$k$H!"(BMeadow $B$N%A%e!<%H%j%"%k$,I=<($5$l$^$9!#(B

Q5: $B$7$P$i$/;H$C$F$$$k$H(B BEP $B$N2;@<$,LD$i$J$/$J$k$N$G$9$,!#(B
A5: $B8=:_$N(B BEP $B$G$O!"2?$i$+$N860x$G2;@<$,=P$J$$>uBV$K$J$k$3$H$,$"$j$^(B
    $B$9!#(BCTRL $B$r2!$7$J$,$i(Be$B$rBG$A!"<!$K(B CTRL $B$r2!$7$J$,$i(Bs$B$rBG$D$H!"H/(B
    $B@<%W%m%0%i%`$@$1$r:F5/F0$9$k$3$H$,$G$-$^$9$N$G$*;n$72<$5$$!#(B

Q6: $B2;@<$N%9%T!<%I$rJQ$($?$$$N$G$9$,!#(B
A6: CTRL $B$r2!$7$J$,$i(Be$B$rBG$A!"<!$KC1FH$N(Bd$B$H?t;z0lJ8;z(B (1$B!A(B9$B$N$I$l$+(B) 
    $B$rF~NO$7$^$9!#$9$k$H!"%9%T!<%I$5$,@_Dj$5$l!"(B"Set speech rate to
    160" $B$N$h$&$K!"@_Dj$5$l$??tCM$r2;@<$G%"%J%&%s%9$7$^$9!#?t;z$O$*9%(B
    $B$_$KD4@a$7$F$/$@$5$$!#?t;z$,Bg$-$/$J$k$[$IB.$/$J$j!">.$5$/$J$k$[$I(B
    $BCY$/$J$j$^$9!#(B


6. $B;29M;qNA(B

Meadow$B$d!"(BEmacs $B$N;H$$J}$r3X$V$N$KLr$KN)$A$=$&$J(B Web $B$r>R2p$7$^$9!#(B

(1) Meadow FAQ
$B!!!!(Bhttp://faq.meadowy.org/

    Meadow $B$K$D$$$F$N<ALd$H2sEz=8$G$9!#(BMeadow $B$K$D$$$F$o$+$i$J$$$3$H$,(B
    $B$"$C$?$i!"$^$:$3$3$r8+$^$7$g$&!#(B

(2) Emacs $B$NM7$SJ}(B
$B!!!!(Bhttp://www.argv.org/bep/common/play_with.html

    Meadow $B$H(B BEP $B$r;H$C$F$NM7$SJ}$N%Z!<%8$G$9!#(B

(3) Edit With Emacs
$B!!!!(Bhttp://webclub.kcom.ne.jp/mb/colo/em_id.html

    Emacs $B$N4pK\E*$JJT=8$NJ}K!$,2r@b$5$l$F$$$^$9!#(B

(4) Emacspeak $B$N%Z!<%8(B ($B1Q8l(B)
$B!!!!(Bhttp://emacspeak.sourceforge.net/

    BEP$B$N85$K$J$C$?(B Emacspeak $B$N%Z!<%8$G$9!#1Q8l$G$9$,!"%f!<%6!<%:%,%$(B
    $B%I$J$I$N%^%K%e%"%k$,FI$a$^$9!#1Q8l$,F@0U$J?M$O!"FI$s$G$_$k$H;29M$K(B
    $B$J$k$+$b$7$l$^$;$s!#(B


7. $B$=$NB>(B

$B$3$N4JC1%$%s%9%H!<%k%Q%C%1!<%8$K4^$^$l$k(B Meadow $B$NK\BN$H%=!<%9%3!<%I$O!"(B
$B0J2<$N>l=j$+$iF~<j$9$k$3$H$,$G$-$^$9!#(B

$B!!!!(Bftp://ftp.m17n.org/pub/mule/Windows/


8. $BO"Mm@h(B

BEP $B$N%W%m%0%i%`$K4X$9$k<ALd!"%P%0%l%]!<%H$O!"(BBEP $B%a!<%j%s%0%j%9%H$X$*(B
$B4j$$$7$^$9!#%a!<%j%s%0%j%9%H$X$N;22C$NJ}K!$O!">e$N(B Q1 $B$r;2>H$7$F$/$@$5(B
$B$$!#$=$NB>!"$4ITL@$JE@$,$"$j$^$7$?$i!"(B

$B!!!!(Bbep-contact@argv.org

$B$^$G!"%a!<%k$G$*Ld$$9g$o$;$/$@$5$$!#(B
