# Millennium / Millennium_Y / Workmod

Millennium, Millennium_Y and Workmod are custom keyboard layouts that are meant to improve touch typing comfort.
Being mostly based on prior work from the AKL community, Millennium tries to avoid the following:

- Commonly used letter combinations under the same finger
- Reusing the same finger in short succession
- Awkward finger stretches in general.

Workmod on the other hand is an adaptation from [Workman](https://workmanlayout.org/) that better suits my preferences (and scores better on analyzers as well).

For reference, _personally_ I feel obligated to note the MTGAP-G variant here (not invented by me) because it deserves recognition and I make no claims of my set of layouts being "better" than that.
MTGAP-G looks like this (use angled):

```
w c l d j k u o p y
r s t h m , a e n i
x v g f b : . / z q
```

As you can see it moves punctuation, which may be too much of a good thing. Millennium/Workmod don't.

Back to Millennium/Workmod.

It goes without saying that the base principle is to keep oft-used keys in easy to reach positions, where the most commonly used letters in English are on "home row".
In addition to the above I've tried to optimize for comfortable movements, such as pressing neighboring keys in order such as with QWERTY's "ER".
The hand-balance (share of strokes typed on left hand versus right hand) is about 46% left and 54% right for both Millennium-variants and 51%/49% L/R for Workmod. For comparison, Colemak-DH roughly has a 44-56 balance.

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

**Keyboard layouts are quite personal and Millennium or Workmod make no ergonomic claims.**
If you are unsure whether trying an alternative keyboard layout such as this might give you Carpal tunnel syndrome or other negative side-effects, just don't do it. Use at your own risk.
What works for me may be bad for you and you should certainly expect that any QWERTY-muscle memory that you had will be negatively affected.

The layouts proper:

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

Workmod (angle):
![Workmod](https://github.com/ijzerbroot/millennium/blob/main/workmod.png)

## Stats

For Millennium, stats from [genkey](https://semilin.github.io/pages/genkey.html) show most movement is on the left index finger (which is fine by me and not extraordinarily high but bear it in mind).
It was run with the _-stagger_ option for regular keyboards and is otherwise unmodified/unconfigured.
Stats depend on a text corpus, which may differ so these "scores" may not be exactly comparable to scores from other genkey-runs that you may find on the internet.
I have added two well-known layouts' stats for reference. One is the well-known Colemak-DH layout and one is the high-performance [Semimak-JQ](https://semilin.github.io) layout (by the creator of genkey as it happens).
Lower scores are "better" in the sense that the scoring-algorithm believes there are fewer undesirable traits such as single-finger repetition, high movement, usage-imbalance between fingers, etc.
It shows that the genkey algorithm considers the Millennium-family to be fairly close to Semimak JQ and notably "better" than Colemak DH for what it's worth. Personal preferences vary considerably and analyzers provide guidance rather than judgment. As _genkey's_ creator puts it: "What matters is not how well the layout fits the metrics, it's how well the metrics fit you".
I have also added stats for column-staggered boards which should work even better with the non-angled versions of Millennium/Y; since I do not own such a board myself I cannot personally judge if the analyzer is correct on that topic.

For Workmod, the genkey score is ever so slightly "worse" than Colemak DH but better than Workman itself. Workmod has a higher movement on the left index finger (lower on the right index though!) than Colemak as well as slightly elevated SFB's. This is a trade-off for more evenness in both hand balance and "rolls" on left and right hand on Workmod.
In addition, Workmod has slightly more hand-alternation than Colemak, which I like.

Generally you may think of Millennium as trying to place highest ranged movement on the easiest-to-move index fingers and putting high-frequency keys ("T" and "A") directly under the strong middle fingers. As a consequence of putting all the vowels on the right hand, this hand sees relatively high usage (but no bottom-row letter movement) for the middle, ring and pinky.
The left hand has less work to do and also has very little bottom-row usage for any finger except the index.
Workmod is a more comfortable (to me) variant of Workman.

Millennium:

```
Millennium
m l d g w  q f o u ,
h r t s y  p n a e i /
z x k c v  j b ' ; .
Rolls (l): 18.56%
        Inward: 6.29%
        Outward: 12.27%
Rolls (r): 28.11%
        Inward: 17.15%
        Outward: 10.96%
Alternates: 36.91%
Onehands: 1.98%
Redirects: 5.74%
Finger Speed (weighted): [0.68 0.89 0.69 3.46 1.04 1.18 1.20 1.17]
Finger Speed (unweighted): [1.02 3.20 3.29 19.01 5.73 5.65 4.33 1.76]
Highest Speed (weighted): 3.46 (LI)
Highest Speed (unweighted): 19.01 (LI)
Index Usage: 16.3% 12.8%
SFBs: 0.854%
DSFBs: 5.864%
LSBs: 1.24%
Top SFBs:
        sc 0.138%       ue 0.129%       ys 0.105%       rl 0.077%
        oa 0.075%       gs 0.061%       nf 0.060%       sy 0.049%

Worst Bigrams:
        ue 17.029       oa 11.602       lr 10.328       sc 9.482
        ws 8.918        mh 8.183        i. 7.824        ,i 7.077

Score: 33.23

```

Millennium Angle:

```
Millennium_angle
m l d g v  q f o u ,
h r t s y  p n a e i /
x k c w z  j b ' ; .
Rolls (l): 18.55%
        Inward: 6.29%
        Outward: 12.26%
Rolls (r): 28.11%
        Inward: 17.15%
        Outward: 10.96%
Alternates: 36.91%
Onehands: 1.98%
Redirects: 5.74%
Finger Speed (weighted): [0.53 1.00 0.89 4.94 1.04 1.18 1.20 1.17]
Finger Speed (unweighted): [0.80 3.60 4.27 27.16 5.73 5.65 4.33 1.76]
Highest Speed (weighted): 4.94 (LI)
Highest Speed (unweighted): 27.16 (LI)
Index Usage: 16.4% 12.8%
SFBs: 0.858%
DSFBs: 5.883%
LSBs: 1.28%
Top SFBs:
        sc 0.138%       ue 0.129%       ys 0.105%       rl 0.077%
        oa 0.075%       gs 0.061%       nf 0.060%       sy 0.049%

Worst Bigrams:
        sc 22.497       ue 17.029       oa 11.602       vc 10.950
        lr 10.328       yc 9.150        mh 8.183        i. 7.824

Score: 38.24
```

Millennium Y:

```
Millennium_Y
m l d g v  q f o u ,
h r t s w  j n a e i /
z x k c b  p y ' ; .
Rolls (l): 18.83%
        Inward: 5.65%
        Outward: 13.17%
Rolls (r): 26.76%
        Inward: 17.03%
        Outward: 9.73%
Alternates: 38.08%
Onehands: 2.30%
Redirects: 5.34%
Finger Speed (weighted): [0.68 0.89 0.69 3.30 1.53 1.18 1.20 1.17]
Finger Speed (unweighted): [1.02 3.20 3.29 18.13 8.42 5.65 4.33 1.76]
Highest Speed (weighted): 3.30 (LI)
Highest Speed (unweighted): 18.13 (LI)
Index Usage: 15.9% 13.2%
SFBs: 0.840%
DSFBs: 6.030%
LSBs: 1.04%
Top SFBs:
        sc 0.138%       ue 0.129%       ny 0.119%       rl 0.077%
        oa 0.075%       gs 0.061%       nf 0.060%       ws 0.042%

Worst Bigrams:
        ue 17.029       oa 11.602       lr 10.328       sc 9.482
        mh 8.183        i. 7.824        np 7.805        sb 7.205

Score: 33.76
```

Millennium Y angle:

```
Millennium_Y_angle
m l d g v  q f o u ,
h r t s b  j n a e i /
x k c w z  p y ' ; .
Rolls (l): 18.81%
        Inward: 5.65%
        Outward: 13.16%
Rolls (r): 26.83%
        Inward: 17.08%
        Outward: 9.76%
Alternates: 37.84%
Onehands: 2.31%
Redirects: 5.50%
Finger Speed (weighted): [0.53 1.00 0.89 4.68 1.78 1.18 1.20 1.17]
Finger Speed (unweighted): [0.80 3.60 4.27 25.71 9.78 5.65 4.33 1.76]
Highest Speed (weighted): 4.68 (LI)
Highest Speed (unweighted): 25.71 (LI)
Index Usage: 15.9% 13.3%
SFBs: 0.846%
DSFBs: 6.057%
LSBs: 1.11%
Top SFBs:
        sc 0.138%       ue 0.129%       ny 0.119%       rl 0.077%
        oa 0.075%       gs 0.061%       nf 0.060%       ws 0.042%

Worst Bigrams:
        sc 22.497       ue 17.029       oa 11.602       vc 10.950
        bc 10.827       lr 10.328       mh 8.183        i. 7.824

Score: 39.18
```

Workmod:

```
Workmod
q d r w b  j f u p ;
a s n t m  y h e i o '
z x g c v  k l , . /
Rolls (l): 22.39%
        Inward: ~14.94%
        Outward: ~7.45%
Rolls (r): 22.07%
        Inward: ~6.71%
        Outward: ~15.36%
Alternates: ~32.26%
Onehands: ~2.00%
Redirects: ~10.43%
Finger Speed (weighted): [0.11 0.91 1.15 6.77 3.57 1.52 1.33 0.59]
Finger Speed (unweighted): [0.16 3.27 5.53 37.24 19.65 7.29 4.80 0.89]
Highest Speed (weighted): 6.77 (LI)
Highest Speed (unweighted): 37.24 (LI)
Index Usage: 20.8% 13.7%
SFBs: 1.812%
DSFBs: 7.432%
LSBs: 1.20%
Top SFBs:
        ly 0.413%       ct 0.370%       e, 0.183%       rn 0.137%
        pi 0.133%       ds 0.132%       ue 0.129%       ip 0.099%

Worst Bigrams:
        yl 25.011       fl 16.660       rn 14.327       pi 13.155
        tc 12.906       ue 12.772       tg 11.795       ds 11.765

Score: 51.21

```

Colemak DH:

```
Colemak DH
q w f p b  j l u y ;
a r s t g  m n e i o '
z x c d v  k h , . /
Rolls (l): 18.04%
        Inward: 11.48%
        Outward: 6.57%
Rolls (r): 28.64%
        Inward: 13.75%
        Outward: 14.89%
Alternates: 30.81%
Onehands: 2.51%
Redirects: 10.74%
Finger Speed (weighted): [0.34 0.48 1.48 3.81 4.84 1.52 1.21 0.59]
Finger Speed (unweighted): [0.50 1.73 7.09 20.94 26.60 7.29 4.34 0.89]
Highest Speed (weighted): 4.84 (RI)
Highest Speed (unweighted): 26.60 (RI)
Index Usage: 19.2% 18.9%
SFBs: 1.092%
DSFBs: 7.903%
LSBs: 1.66%
Top SFBs:
        e, 0.183%       sc 0.138%       ue 0.129%       y. 0.087%
        nk 0.079%       pt 0.078%       nl 0.068%       kn 0.055%

Worst Bigrams:
        lh 13.082       ue 12.772       lk 11.823       sc 10.865
        y. 10.820       fc 9.643        mn 9.623        bt 9.544

Score: 44.53
```

Workman (the original, non angled):

```
Workman
q d r w b  j f u p ;
a s h t g  y n e o i '
z x m c v  k l , . /
Rolls (l): 21.25%
        Inward: 9.28%
        Outward: 11.97%
Rolls (r): 22.98%
        Inward: 14.62%
        Outward: 8.35%
Alternates: 30.00%
Onehands: 3.14%
Redirects: 10.53%
Finger Speed (weighted): [0.34 0.86 3.28 3.78 4.89 1.52 2.01 0.73]
Finger Speed (unweighted): [0.50 3.09 15.73 20.80 26.89 7.29 7.25 1.09]
Highest Speed (weighted): 4.89 (RI)
Highest Speed (unweighted): 26.89 (RI)
Index Usage: 18.4% 16.0%
SFBs: 2.370%
DSFBs: 7.500%
LSBs: 1.40%
Top SFBs:
        ly 0.413%       ct 0.370%       po 0.296%       op 0.235%
        e, 0.183%       rm 0.136%       ds 0.132%       ue 0.129%

Worst Bigrams:
        rm 39.302       yl 25.011       po 23.386       fl 16.660
        tc 12.906       ue 12.772       ds 11.765       rh 9.652

Score: 54.34
```

Semimak JQ:

```
Semimak JQ
f l h v z  ' w u o y
s r n t k  c d e a i ;
x j b m q  p g , . /
Rolls (l): 17.37%
        Inward: 7.81%
        Outward: 9.56%
Rolls (r): 25.32%
        Inward: 12.56%
        Outward: 12.76%
Alternates: 40.59%
Onehands: 1.88%
Redirects: 6.57%
Finger Speed (weighted): [0.75 0.76 0.75 1.06 1.80 1.52 2.15 1.04]
Finger Speed (unweighted): [1.12 2.72 3.61 5.82 9.92 7.29 7.73 1.56]
Highest Speed (weighted): 2.15 (RR)
Highest Speed (unweighted): 9.92 (RI)
Index Usage: 13.4% 13.1%
SFBs: 0.693%
DSFBs: 5.795%
LSBs: 1.92%
Top SFBs:
        e, 0.183%       ue 0.129%       rl 0.077%       oa 0.075%
        yi 0.037%       tm 0.028%       dg 0.026%       a. 0.024%

Worst Bigrams:
        oa 15.469       o. 14.631       ue 12.772       yi 11.385
        lr 10.328       fs 7.891        e, 7.262        hn 6.649

Score: 31.48
```

MTGAP-G (angled):

```
MTGAPG
w c l d j  k u o p y
r s t h m  , a e n i
x v g f b  : . / z q
Missing characters: [; ']
Rolls (l): 18.17%
        Inward: 13.35%
        Outward: 4.82%
Rolls (r): 24.77%
        Inward: 13.71%
        Outward: 11.06%
Alternates: 39.43%
Onehands: 2.20%
Redirects: 5.05%
Finger Speed (weighted): [1.04 1.35 2.21 4.62 2.35 1.62 0.40 0.95]
Finger Speed (unweighted): [1.57 4.87 10.62 25.42 12.95 7.76 1.45 1.43]
Highest Speed (weighted): 4.62 (LI)
Highest Speed (unweighted): 25.42 (LI)
Index Usage: 16.6% 13.8%
SFBs: 1.332%
DSFBs: 6.441%
LSBs: 0.80%
Top SFBs:
        gh 0.239%       ak 0.153%       sc 0.138%       au 0.127%
        ua 0.111%       lt 0.110%       tl 0.095%       mb 0.079%

Worst Bigrams:
        oe 23.001       lv 16.751       wr 16.107       cs 14.486
        hg 14.076       ka 12.647       lt 12.397       dg 11.644

Score: 45.30
```

## Stats for column-staggered keyboards.

Millennium:

```
Millennium
m l d g w  q f o u ,
h r t s y  p n a e i /
z x k c v  j b ' ; .
Rolls (l): 18.56%
        Inward: 6.29%
        Outward: 12.27%
Rolls (r): 28.11%
        Inward: 17.15%
        Outward: 10.96%
Alternates: 36.91%
Onehands: 1.98%
Redirects: 5.74%
Finger Speed (weighted): [0.68 0.89 0.69 3.46 1.04 1.18 1.20 1.17]
Finger Speed (unweighted): [1.02 3.20 3.29 19.01 5.73 5.65 4.33 1.76]
Highest Speed (weighted): 3.46 (LI)
Highest Speed (unweighted): 19.01 (LI)
Index Usage: 16.3% 12.8%
SFBs: 0.854%
DSFBs: 5.864%
LSBs: 1.24%
Top SFBs:
        sc 0.138%       ue 0.129%       ys 0.105%       rl 0.077%
        oa 0.075%       gs 0.061%       nf 0.060%       sy 0.049%

Worst Bigrams:
        ue 17.029       oa 11.602       lr 10.328       sc 9.482
        ws 8.918        mh 8.183        i. 7.824        ,i 7.077

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
