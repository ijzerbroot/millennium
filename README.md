# Millennium
A keyboard layout

Millennium is a custom keyboard layout that is meant to improve touch typing comfort.
It takes care to avoid the following:
* Commonly used letter combinations under the same finger
* Reusing the same finger in short succession
* Awkward finger stretches in general.

It goes without saying that the base principle is to keep oft-used keys in easy to reach positions, where the most commonly used letters in English are on "home row".
In addition to the above it tries to optimize for comfortable movements, such as pressing neighboring keys in order such as QWERTY's "ER". 

It started from combining a few traits from layouts created by the AKL community.
Inspiration came mainly from the excellent [Maya](https://docs.google.com/document/u/0/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/mobilebasic#h.15eb7sf9z9p9) and [Sturdy](https://docs.google.com/document/u/0/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/mobilebasic#h.gmmedttxvbs3) layouts. Kudos to Adi.Lela and Oxey.

Where it mostly differs from the two inspirations is in placing H and M on left pinky, thereby avoiding an NH column or an N-pinky, neither of which I liked very much. 
As both H and M are relatively low-frequency letters in English it feels to me that this is easily handled.

To my hands it feels uncomfortable to have movements like (in QWERTY-speak): "AW", "AE", "RD", "AD".
In the millennium layout they have become "HL", "HD", "GT" and "HT", which are much less common in my daily typing.
NOTE: "TH" in millennium moves from middle finger to pinky, which is definitely not the same thing as the other way around. "TH" on millennium works fine for me.

Some letter-combinations that I think work particularly well on Millennium are words like "and", "note", "hold", "under", "test", "get", "starts" but even with M on pinky a word like "must" flows nicely.
Opinions may differ on this but it works for me!

## Word of warning
**Keyboard layouts are quite personal and Millennium makes no ergonomic claims.**
If you are unsure whether trying an alternative keyboard layout such as this might give you Carpal tunnel syndrome or similar negative side-effects, just don't do it. Use at your own risk. 
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
