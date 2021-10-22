# Vjezba0
Priprema za vjezbu1/2

50 50 translate
/mreza {0.5 0.3 0 0 setcmykcolor 
gsave
2 setlinewidth 500 0 moveto 0 0 lineto 0 500 lineto stroke
grestore
gsave
0.3 setlinewidth
5 { 30 100 moveto 500 100 lineto stroke 0 100 translate } repeat
grestore
gsave
0.3 setlinewidth
5 { 100 20 moveto 100 500 lineto stroke 100 0 translate } repeat
grestore
gsave
/tekst 3 string def /Helvetica findfont 10 scalefont setfont
100 100 500 { /y exch def 5 y 2 sub moveto y tekst cvs show } for
90 100 500 { /x exch def x 5 moveto x 10 add tekst cvs show } for
grestore 
0 setgray } bind def
mreza

%Trokut
0.5 setgray
100 100 moveto
300 100 lineto
200 300 lineto
closepath
1 setlinecap
1 setlinejoin
fill

%Obrub
0 setgray
1 setlinecap
100 100 moveto
200 0 rlineto
-100 200 rlineto
closepath
3 setlinewidth
stroke


%Gornji dio trokuta
0.9 setgray
1 setlinecap
200 304 moveto
-20 -40 rlineto
10 -10 rlineto
10 10 rlineto
10 -15 rlineto
10 15 rlineto
closepath

fill
0 setlinewidth

stroke

%strijelica 1 

4 setlinewidth
150 103 moveto
0 50 rlineto
0 setlinecap
1 setgray stroke

135 140 moveto
150 155 lineto
165 140 lineto
1 setgray stroke

135 120 moveto
150 135 lineto
165 120 lineto
1 setgray stroke

%strijelica 2 

4 setlinewidth
200 103 moveto
0 100 rlineto
0 setlinecap
1 setgray stroke

1 setlinecap
185 190 moveto
200 205 lineto
215 190 lineto
1 setgray stroke

185 170 moveto
200 185 lineto
215 170 lineto
1 setgray stroke

185 150 moveto
200 165 lineto
215 150 lineto
1 setgray stroke

%strijelica 3 

4 setlinewidth
250 103 moveto
0 50 rlineto
0 setlinecap
1 setgray stroke

235 140 moveto
250 155 lineto
265 140 lineto
1 setgray stroke

235 120 moveto
250 135 lineto
265 120 lineto
1 setgray stroke
showpage
