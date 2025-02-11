java c
ELEN   4810   Final   Exam


1.      The   Z-transform.   Consider   the   following   pole-zero   diagram:





Please   answer   the   following   questions:
(a).   Suppose   that   the   system   is   stable.    What   is   the   region   of convergence?    Is   the   system   causal?
(b).   At   what   frequency   or   frequencies   W   is   jH(ej!   )j   maximized?
(c).   At   what   frequency   or   frequencies   W   is   the   group   delay   grd[H(ej!   )]   maximized?
(d).   Which   of   the   following   best   characterizes   the   system?
LOWPASS                        HIGHPASS                           ALLPASS                        BANDPASS                           BANDSTOP
(e).      Suppose   we   express   H(z)   as   H(z)   = Hmin   (z)Hap   (z),   where   Hmin      is   minimum   phase,   and   Hap is   all-pass.   Please   sketch   the   pole-zero   diagrams   of   Hmin    and   Happ   ,   labeling   poles   and   zeros.




2.      Bilinear   Transformation.   We design an IIR discrete time   ﬁlter,   by   starting   from   a   continuous   design   Hc   (s)   with   magnitude   response   Hc   (jΩ)   as   below:

You   may   assume   that   this   ﬁlter   was   designed   to   approximate   an   ideal   low-pass   ﬁlter   with   cutof   frequency   Ωc    = tan(π/16).   We   set

and

Please   answer   the   following   questions:
(a) Which   of   the   following   types   of   ﬁlter   is   Hc   (s)?
BUTTERWORTH                      CHEBYSCHEV I                      CHEBYSCHEV   II                        ELLIPTIC
(b)   Please   sketch   jH(ejω   )j      over   the   interval   [0,   π],   labelling   any   cutof   frequencies,   and   indicating which   intervals   of ω   exhibit   ripple.
(c)   Let   β1, . . . ,   βN      be   the   zeros   of   Hc   (s).    Please   give   an   expression   for   the   zeros   ζi      of   H(z)   in   terms of   β1, . . .   ,   βN .
(d)   Please   give   an   expression   for   the   impulse   response   h[n]   in   terms   of the   impulse   response   h1 [n].
(e)   Suppose   we   wish   to   achieve   a   sharper   transition,   without   increasing   the   order   of   the   ﬁlter.    How can   we   modify   our   initial   design   Hc   (s)   to   accomplish   this?




3.       FIR   Filter   Design.      Consider   two   designs   of   ﬁnite   impulse   response   (FIR)   bandpass   ﬁlters.   Both   designs   have   a   target   magnitude   response





We   plot   the   gain   20   log1   0jHj   and   phase   \H   for   each:





Please   answer   the   following   questions:
(a).   Which   ﬁlter   has   the   shorter   length   L?
(b).   Both   ﬁlters   are   canonical   generalized   li代 写ELEN 4810 Final Exam 2021Matlab
代做程序编程语言near   phase   systems.   What   type   are   they,   and   why?
(c).      For   the   bottom   design   (H2   ),   please   use   Chebyschev’s   alternation   theorem   to   give   an   upper bound   on   the   length   L   of the   ﬁlter.




4.    Inverse   Systems.   Consider   an   LTI   system   with   impulse   response
h[n]   =   δ[n] — 4δ[n   — 2].
Let   H(ej!   )   denote   its   frequency   response.
Recall   that   an   inverse      system   for   h   with   impulse   response   hi   [n] satisﬁes   hi   * (h   *   x)[n]   = x[n]   for   any input   x   with   ROC(x) ∩ ROC(h) ∩ ROC(hi   ) ≠ 0,   and   ROC(h) ∩ ROC(hi   ) ≠   0.
(a)   Find   the   impulse   response   hi [n]   of a   stable   inverse   system   for   h[n].   Is   your   answer   causal?
(b)   Find   an   impulse   response   g[n]   of   a   system   whose   magnitude   response   is   the   same   as   jH(ej!   )j   (i.e.,   jG(ej!   )j   =   jH(ej!   )j   for   all   ω),   but   which   has   a   causal,   stable   inverse   system.




5.    Systems   and   Spectrograms.   A   continuous   time   “chirp”   signalxc   (t) =   cos(Qt2   )                                                                                                                                                                                          (10)is   sampled   with   period   T   =   10-4s   to   produce   a   discrete-time   signal   x[n] = xc   (nT).    The   signal   x[n]   is   then   passed   through   a   stable   LTI   system   with   real-valued   impulse   response   h[n]   to   produce   an output   signal   y[n].
We   generate   spectrograms   of   jX[r,   k]j    and   jY   [r,   k]j   with   a   Hamming   window   w[n]   of   length   100,   a   time   step   R   =   10,   and   a   length-N   = 200   DFT.   More   precisely,X[r,   k]         =       DFTN   {w[n]x[n +   rR]} [k].                                                                                                                              (11)
Y   [r,   k]         =         DFTN   {w[n]y[n + rR]}   [k].                                                                                                                              (12)
The   two   spectrograms   jX[r, k]j   and   jY   [r, k]j   are   displayed   below,   for   r   = 0, . . .   45   and   k   = 0, . . . 100.



(a)   What   is   the   chirp   parameter   Q?   Please   make   the   best   estimate   you   can.
(b)   Please   sketch   the   group   delay   grd(H(ej!   )   as   a   function   of   ω   .      Please   label   the   locations   and heights   of   any   local   maxima   or   minima.   You   can   use   the   axis   on   the   following   page   for   your   sketch.

   
   



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
