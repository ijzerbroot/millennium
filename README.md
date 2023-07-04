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
It was run with the _-stagger_ option for regular keyboards.

Millennium:
```
Millennium
m l d g w q f o u ,
h r t s y p n a e i /
z x k c v j b ' ; .
0 1 2 3 3 4 4 5 6 7
0 1 2 3 3 4 4 5 6 7 7
0 1 2 3 3 4 4 5 6 7
Rolls (l): 19.81%
	Inward: ~6.17%
	Outward: ~13.64%
Rolls (r): 20.13%
	Inward: ~11.85%
	Outward: ~8.28%
Alternates: ~40.10%
Onehands: ~2.60%
Redirects: ~8.28%
Finger Speed (weighted): [1.69 1.91 0.72 6.80 3.03 1.89 1.66 3.97]
Finger Speed (unweighted): [2.54 6.89 3.44 37.38 16.64 9.05 5.99 5.95]
Highest Speed (weighted): 6.80 (LI)
Highest Speed (unweighted): 37.38 (LI)
Index Usage: 18.7% 14.0%
SFBs: 2.057%
DSFBs: 8.439%
LSBs: 1.37%
Top SFBs:
	oa 0.478%	nf 0.239%	gs 0.239%	vg 0.239%
	cs 0.239%	rl 0.119%	gc 0.119%	/. 0.119%

Worst Bigrams:
	i/ 46.390	gv 41.943	lr 27.602	ue 24.896
	oa 22.516	sc 15.839	gc 14.624	hz 11.615

Score: 67.77
```

Millennium Angle:
```
Millennium_angle
m l d g v q f o u ,
h r t s y p n a e i /
x k c w z j b ' ; .
0 1 2 3 3 4 4 5 6 7
0 1 2 3 3 4 4 5 6 7 7
1 2 3 3 3 4 4 5 6 7
Millennium_angle
m l d g v  q f o u ,
h r t s y  p n a e i /
x k c w z  j b ' ; .
Rolls (l): 19.64%
	Inward: ~6.01%
	Outward: ~13.64%
Rolls (r): 20.13%
	Inward: ~11.85%
	Outward: ~8.28%
Alternates: ~40.10%
Onehands: ~2.60%
Redirects: ~7.95%
Finger Speed (weighted): [0.60 1.91 0.71 6.32 3.03 1.89 1.66 3.97]
Finger Speed (unweighted): [0.89 6.89 3.41 34.76 16.64 9.05 5.99 5.95]
Highest Speed (weighted): 6.32 (LI)
Highest Speed (unweighted): 34.76 (LI)
Index Usage: 19.1% 14.0%
SFBs: 2.253%
DSFBs: 8.237%
LSBs: 1.47%
Top SFBs:
	oa 0.478%	vg 0.239%	cs 0.239%	zs 0.239%
	gs 0.239%	nf 0.239%	/. 0.119%	ue 0.119%

Worst Bigrams:
	i/ 46.390	lr 27.602	ue 24.896	oa 22.516
	sz 18.435	vc 17.092	sc 15.839	gc 12.495

Score: 63.25
```

Millennium Y:
```
Millennium_Y
m l d g v q f o u ,
h r t s w j n a e i /
z x k c b p y ' ; .
0 1 2 3 3 4 4 5 6 7
0 1 2 3 3 4 4 5 6 7 7
0 1 2 3 3 4 4 5 6 7
Millennium_Y
m l d g v  q f o u ,
h r t s w  j n a e i /
z x k c b  p y ' ; .
Rolls (l): 20.94%
	Inward: ~5.36%
	Outward: ~15.58%
Rolls (r): 17.37%
	Inward: ~10.06%
	Outward: ~7.31%
Alternates: ~43.83%
Onehands: ~2.60%
Redirects: ~6.33%
Finger Speed (weighted): [1.69 1.91 0.72 7.04 2.95 1.89 1.66 3.97]
Finger Speed (unweighted): [2.54 6.89 3.44 38.71 16.23 9.05 5.99 5.95]
Highest Speed (weighted): 7.04 (LI)
Highest Speed (unweighted): 38.71 (LI)
Index Usage: 20.1% 12.6%
SFBs: 1.959%
DSFBs: 9.132%
LSBs: 1.37%
Top SFBs:
	oa 0.478%	vg 0.239%	cs 0.239%	nf 0.239%
	gs 0.239%	/. 0.119%	jq 0.119%	ue 0.119%

Worst Bigrams:
	i/ 46.390	lr 27.602	sb 27.458	ue 24.896
	oa 22.516	sc 15.839	qp 15.746	gc 14.624

Score: 69.09
```

Millennium Y angle:
```
Millennium_Y_angle
m l d g v  q f o u ,
h r t s b  j n a e i /
x k c w z  p y ' ; .
0 1 2 3 3 4 4 5 6 7
0 1 2 3 3 4 4 5 6 7 7
1 2 3 3 3 4 4 5 6 7
Millennium_Y_angle
m l d g v  q f o u ,
h r t s b  j n a e i /
x k c w z  p y ' ; .
Rolls (l): 21.10%
	Inward: ~5.19%
	Outward: ~15.91%
Rolls (r): 17.05%
	Inward: ~9.90%
	Outward: ~7.14%
Alternates: ~43.83%
Onehands: ~2.60%
Redirects: ~6.49%
Finger Speed (weighted): [0.60 1.91 0.71 6.52 3.63 1.89 1.66 3.97]
Finger Speed (unweighted): [0.89 6.89 3.41 35.85 19.97 9.05 5.99 5.95]
Highest Speed (weighted): 6.52 (LI)
Highest Speed (unweighted): 35.85 (LI)
Index Usage: 20.1% 13.0%
SFBs: 1.959%
DSFBs: 9.131%
LSBs: 1.67%
Top SFBs:
	oa 0.478%	gs 0.239%	cs 0.239%	vg 0.239%
	nf 0.239%	nj 0.119%	sc 0.119%	py 0.119%

Worst Bigrams:
	i/ 46.390	lr 27.602	ue 24.896	oa 22.516
	bc 20.770	vc 17.092	sc 15.839	qp 15.746

Score: 66.44
```
