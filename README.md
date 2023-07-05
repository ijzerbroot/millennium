# Millennium / Millennium_Y

Millennium and Millennium_Y are custom keyboard layouts that are meant to improve touch typing comfort.
I took care to avoid the following:
* Commonly used letter combinations under the same finger
* Reusing the same finger in short succession
* Awkward finger stretches in general.

It goes without saying that the base principle is to keep oft-used keys in easy to reach positions, where the most commonly used letters in English are on "home row".
In addition to the above I've tried to optimize for comfortable movements, such as pressing neighboring keys in order such as with QWERTY's "ER".
The hand-balance (share of strokes typed on left hand versus right hand) is about 46% left and 54% right for both Millennium-variants. For comparison, Colemak-DH roughly has a 44-56 balance.

Millennium and its Millennium_Y variant started from combining a few traits from layouts created by the AKL community.
Inspiration came mainly from the excellent [Maya](https://docs.google.com/document/u/0/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/mobilebasic#h.15eb7sf9z9p9) and [Sturdy](https://docs.google.com/document/u/0/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/mobilebasic#h.gmmedttxvbs3) layouts. Kudos to Adi.Lela and Oxey.

Where they mostly differ from the two inspirations is in placing H and M on left pinky, thereby avoiding an NH column or an N-pinky, neither of which I liked very much. 
As both H and M are relatively low-frequency letters in English it feels to me that this is easily handled and "mother" is still comparatively easy to type despite having an M and an H.

To my hands it feels uncomfortable to have movements like (in QWERTY-speak): "AW", "AE", "RD", "AD".
In the millennium layouts they have become "HL", "HD", "GT" and "HT", which are much less common in my daily typing.
NOTE: "TH" in millennium moves from middle finger to pinky, which is definitely not the same thing as the other way around. "TH" on millennium works fine for me.

Some letter-combinations that I think work particularly well on Millennium are words like "and", "note", "hold", "under", "test", "get", "starts" but even with M on pinky a word like "must" flows nicely.
Opinions may differ on this but it works for me!

## Word of warning
**Keyboard layouts are quite personal and Millennium makes no ergonomic claims.**
If you are unsure whether trying an alternative keyboard layout such as this might give you Carpal tunnel syndrome or other negative side-effects, just don't do it. Use at your own risk. 
What works for me may be bad for you and you should certainly expect that any QWERTY-muscle memory that you had will be negatively affected.

The layout proper:

Using angle mod (you type QWERTY C with your left index finger):
![Millennium Angle](https://github.com/ijzerbroot/millennium/blob/main/millennium-angle.png)

Without angle mod (you type QWERTY C with your left middle finger):
![Millennium](https://github.com/ijzerbroot/millennium/blob/main/millennium.png)


There is an alternative swap possible that will provide a more even load on the index fingers and makes the "my" and "sy" bigrams better.
It may be preferable to some.

Millennium_y (angle mod):
![Millennium Y](https://github.com/ijzerbroot/millennium/blob/main/millennium_y_angle.png)

Millennium_y (without angle mod):
![Millennium Y](https://github.com/ijzerbroot/millennium/blob/main/millennium_y.png)


## Stats
Stats from [genkey](https://semilin.github.io/pages/genkey.html) show most movement is on the left index finger (which is fine by me and not extraordinarily high but bear it in mind). 
It was run with the _-stagger_ option for regular keyboards and is otherwise unmodified/unconfigured.
Stats depend on a text corpus, which may differ so these "scores" may not be exactly comparable to scores from other genkey-runs that you may find on the internet. 
I have added two well-known layouts' scoring for reference. One is the well-known Colemak-DH layout and one is the high-performance [Semimak-JQ](https://semilin.github.io) layout (by the creator of genkey as it happens).
Lower scores are better. It shows that the genkey algorithm considers the Millennium-family to be close to Semimak JQ and considerably "better" than Colemak DH for what it's worth. Personal preferences may be different and analyzers provide guidance rather than judgment. I personally believe that scores within about 5 points of each other are likely more a matter of personal preference than signifying "better" or "worse" in absolute terms. 
I have also added stats for column-staggered boards which should work even better with the non-angled versions of Millennium/Y; since i do not own such a board myself I cannot personally judge if the analyzer is correct on that topic.

Millennium:
```
Millennium
m l d g w  q f o u ,
h r t s y  p n a e i /
z x k c v  j b ' ; .
Rolls (l): 18.56%
	Inward: ~6.29%
	Outward: ~12.27%
Rolls (r): 28.11%
	Inward: ~17.15%
	Outward: ~10.96%
Alternates: ~36.91%
Onehands: ~1.98%
Redirects: ~5.74%
Finger Speed (weighted): [0.76 0.99 0.79 3.90 1.14 1.33 1.32 1.40]
Finger Speed (unweighted): [1.14 3.57 3.79 21.44 6.27 6.40 4.75 2.10]
Highest Speed (weighted): 3.90 (LI)
Highest Speed (unweighted): 21.44 (LI)
Index Usage: 16.3% 12.8%
SFBs: 0.854%
DSFBs: 5.864%
LSBs: 0.66%
Top SFBs:
	sc 0.138%	ue 0.129%	ys 0.105%	rl 0.077%
	oa 0.075%	gs 0.061%	nf 0.060%	sy 0.049%

Worst Bigrams:
	ue 18.490	sc 12.736	oa 12.597	lr 11.214
	i. 10.508	mh 8.885	sv 8.833	,i 7.684

Score: 36.62
```

Millennium Angle:
```
Millennium_angle
m l d g v  q f o u ,
h r t s y  p n a e i /
x k c w z  j b ' ; .
Rolls (l): 18.55%
	Inward: ~6.29%
	Outward: ~12.26%
Rolls (r): 28.11%
	Inward: ~17.15%
	Outward: ~10.96%
Alternates: ~36.91%
Onehands: ~1.98%
Redirects: ~5.74%
Finger Speed (weighted): [0.58 0.96 0.76 3.84 1.14 1.33 1.32 1.40]
Finger Speed (unweighted): [0.87 3.47 3.64 21.13 6.27 6.40 4.75 2.10]
Highest Speed (weighted): 3.84 (LI)
Highest Speed (unweighted): 21.13 (LI)
Index Usage: 16.4% 12.8%
SFBs: 0.858%
DSFBs: 5.883%
LSBs: 0.66%
Top SFBs:
	sc 0.138%	ue 0.129%	ys 0.105%	rl 0.077%
	oa 0.075%	gs 0.061%	nf 0.060%	sy 0.049%

Worst Bigrams:
	ue 18.490	sc 12.736	oa 12.597	lr 11.214
	i. 10.508	mh 8.885	,i 7.684	vc 7.066

Score: 35.75
```

Millennium Y:
```
Millennium_Y
m l d g v  q f o u ,
h r t s w  j n a e i /
z x k c b  p y ' ; .
Rolls (l): 18.83%
	Inward: ~5.65%
	Outward: ~13.17%
Rolls (r): 26.76%
	Inward: ~17.03%
	Outward: ~9.73%
Alternates: ~38.08%
Onehands: ~2.30%
Redirects: ~5.34%
Finger Speed (weighted): [0.76 0.99 0.79 3.87 1.46 1.33 1.32 1.40]
Finger Speed (unweighted): [1.14 3.57 3.79 21.26 8.02 6.40 4.75 2.10]
Highest Speed (weighted): 3.87 (LI)
Highest Speed (unweighted): 21.26 (LI)
Index Usage: 15.9% 13.2%
SFBs: 0.840%
DSFBs: 6.030%
LSBs: 0.16%
Top SFBs:
	sc 0.138%	ue 0.129%	ny 0.119%	rl 0.077%
	oa 0.075%	gs 0.061%	nf 0.060%	ws 0.042%

Worst Bigrams:
	ue 18.490	sc 12.736	oa 12.597	sb 12.415
	lr 11.214	i. 10.508	mh 8.885	,i 7.684

Score: 36.72
```

Millennium Y angle:
```
Millennium_Y_angle
m l d g v  q f o u ,
h r t s b  j n a e i /
x k c w z  p y ' ; .
Rolls (l): 18.81%
	Inward: ~5.65%
	Outward: ~13.16%
Rolls (r): 26.83%
	Inward: ~17.08%
	Outward: ~9.76%
Alternates: ~37.84%
Onehands: ~2.31%
Redirects: ~5.50%
Finger Speed (weighted): [0.58 0.96 0.76 3.52 1.63 1.33 1.32 1.40]
Finger Speed (unweighted): [0.87 3.47 3.64 19.38 8.97 6.40 4.75 2.10]
Highest Speed (weighted): 3.52 (LI)
Highest Speed (unweighted): 19.38 (LI)
Index Usage: 15.9% 13.3%
SFBs: 0.846%
DSFBs: 6.057%
LSBs: 0.14%
Top SFBs:
	sc 0.138%	ue 0.129%	ny 0.119%	rl 0.077%
	oa 0.075%	gs 0.061%	nf 0.060%	ws 0.042%

Worst Bigrams:
	ue 18.490	sc 12.736	oa 12.597	lr 11.214
	i. 10.508	mh 8.885	,i 7.684	vc 7.066

Score: 35.43
```

Colemak DH:
```
Colemak DH
q w f p b  j l u y ;
a r s t g  m n e i o '
z x c d v  k h , . /
Rolls (l): 18.04%
	Inward: ~11.48%
	Outward: ~6.57%
Rolls (r): 28.64%
	Inward: ~13.75%
	Outward: ~14.89%
Alternates: ~30.81%
Onehands: ~2.51%
Redirects: ~10.74%
Finger Speed (weighted): [0.42 0.53 1.85 4.00 4.90 1.79 1.44 0.60]
Finger Speed (unweighted): [0.63 1.91 8.87 21.99 26.95 8.59 5.18 0.90]
Highest Speed (weighted): 4.90 (RI)
Highest Speed (unweighted): 26.95 (RI)
Index Usage: 19.2% 18.9%
SFBs: 1.092%
DSFBs: 7.903%
LSBs: 1.12%
Top SFBs:
	e, 0.183%	sc 0.138%	ue 0.129%	y. 0.087%
	nk 0.079%	pt 0.078%	nl 0.068%	kn 0.055%

Worst Bigrams:
	lh 15.644	sc 14.593	ue 13.868	y. 12.940
	fc 11.532	e, 9.753	mn 9.623	mh 9.123

Score: 47.81
```

Semimak JQ:
```
Semimak JQ
f l h v z  ' w u o y
s r n t k  c d e a i ;
x j b m q  p g , . /
Rolls (l): 17.37%
	Inward: ~7.81%
	Outward: ~9.56%
Rolls (r): 25.32%
	Inward: ~12.56%
	Outward: ~12.76%
Alternates: ~40.59%
Onehands: ~1.88%
Redirects: ~6.57%
Finger Speed (weighted): [0.84 0.83 0.87 1.18 1.97 1.79 2.49 1.16]
Finger Speed (unweighted): [1.26 2.99 4.18 6.51 10.85 8.59 8.96 1.74]
Highest Speed (weighted): 2.49 (RR)
Highest Speed (unweighted): 10.85 (RI)
Index Usage: 13.4% 13.1%
SFBs: 0.693%
DSFBs: 5.795%
LSBs: 1.01%
Top SFBs:
	e, 0.183%	ue 0.129%	rl 0.077%	oa 0.075%
	yi 0.037%	tm 0.028%	dg 0.026%	a. 0.024%

Worst Bigrams:
	o. 17.497	oa 16.796	ue 13.868	yi 12.362
	lr 11.214	e, 9.753	tm 8.919	fs 8.568

Score: 34.50
```

## Stats for column-staggered keyboards.

Millennium:
```
Millennium
m l d g w  q f o u ,
h r t s y  p n a e i /
z x k c v  j b ' ; .
Rolls (l): 18.56%
	Inward: ~6.29%
	Outward: ~12.27%
Rolls (r): 28.11%
	Inward: ~17.15%
	Outward: ~10.96%
Alternates: ~36.91%
Onehands: ~1.98%
Redirects: ~5.74%
Finger Speed (weighted): [0.68 0.89 0.69 3.46 1.04 1.18 1.20 1.17]
Finger Speed (unweighted): [1.02 3.20 3.29 19.01 5.73 5.65 4.33 1.76]
Highest Speed (weighted): 3.46 (LI)
Highest Speed (unweighted): 19.01 (LI)
Index Usage: 16.3% 12.8%
SFBs: 0.854%
DSFBs: 5.864%
LSBs: 1.24%
Top SFBs:
	sc 0.138%	ue 0.129%	ys 0.105%	rl 0.077%
	oa 0.075%	gs 0.061%	nf 0.060%	sy 0.049%

Worst Bigrams:
	ue 17.029	oa 11.602	lr 10.328	sc 9.482
	ws 8.918	mh 8.183	i. 7.824	,i 7.077

Score: 33.23
```

Millennium Y:
```
Millennium_Y
m l d g v  q f o u ,
h r t s w  j n a e i /
z x k c b  p y ' ; .
Rolls (l): 18.83%
	Inward: ~5.65%
	Outward: ~13.17%
Rolls (r): 26.76%
	Inward: ~17.03%
	Outward: ~9.73%
Alternates: ~38.08%
Onehands: ~2.30%
Redirects: ~5.34%
Finger Speed (weighted): [0.68 0.89 0.69 3.30 1.53 1.18 1.20 1.17]
Finger Speed (unweighted): [1.02 3.20 3.29 18.13 8.42 5.65 4.33 1.76]
Highest Speed (weighted): 3.30 (LI)
Highest Speed (unweighted): 18.13 (LI)
Index Usage: 15.9% 13.2%
SFBs: 0.840%
DSFBs: 6.030%
LSBs: 1.04%
Top SFBs:
	sc 0.138%	ue 0.129%	ny 0.119%	rl 0.077%
	oa 0.075%	gs 0.061%	nf 0.060%	ws 0.042%

Worst Bigrams:
	ue 17.029	oa 11.602	lr 10.328	sc 9.482
	mh 8.183	i. 7.824	np 7.805	sb 7.205

Score: 33.76
```
