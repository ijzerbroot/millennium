# Millennium / Millennium_Y / Orderly / Rest

Millennium, Millennium_Y, Orderly and Rest are custom keyboard layouts that are meant to improve touch typing comfort (for me at least!)
Being mostly based on prior work from the AKL community, Millennium tries to avoid the following:

- Commonly used letter combinations under the same finger
- Reusing the same finger in short succession
- Awkward finger stretches in general.

`Orderly` is my heavily modified take on the wonderful [Boo layout](https://ballerboo.github.io/boolayout/) that I personally found too difficult to use.
Orderly could be considered Boo-for-dummies, especially the ZXC-variant that keeps some QWERTY keys in place.
It is currently (2024) my favorite layout because of how it flows. It is however not the most _theoretically efficient_ layout imaginable (but not too bad either).
The non-ZXV variant was adapted to suggestions made by Ian Douglas of [keyboard-design](https://www.keyboard-design.com/) fame. It generally improves left-hand motion but gives up QWERTY ZXC and G.

`Rest` on the other hand is an adaptation of QWERTY's hand distribution (rhythm) that better suits my preferences (and scores better on genkey as well).
The idea behind `Rest` is to keep some vague semblance to QWERTY while prioritizing my personal comfort. The only keys that change hands are `M` and `F` and arguably `B`/`K` if you would tend to use your left hand for the B-key.

It goes without saying that the base principle for all these layouts is to keep oft-used keys in easy to reach positions, where the most commonly used letters in English are on "home row".
In addition to the above I've tried to optimize for comfortable movements, such as pressing neighboring keys in order such as with QWERTY's "ER".
The hand-balance (share of strokes typed on left hand versus right hand) is about 46% left and 54% right for both Millennium-variants, 49/51 for Orderly and 50/50 L/R for Rest. For comparison, Colemak-DH roughly has a 44-56 balance.

Millennium and its Millennium_Y variant started from combining a few traits from layouts created by the AKL community.
Inspiration came mainly from the excellent [Maya](https://docs.google.com/document/u/0/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/mobilebasic#h.15eb7sf9z9p9) and [Sturdy](https://docs.google.com/document/u/0/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/mobilebasic#h.gmmedttxvbs3) layouts. Kudos to Adi.Lela and Oxey.

Where they mostly differ from the two inspirations is in placing H and M on left pinky, thereby avoiding an NH column or an N-pinky, neither of which I liked very much.
As both H and M are relatively low-frequency letters in English it feels to me that this is easily handled and "mother" is still comparatively easy to type despite having an M and an H.

NOTE: "TH" in millennium moves from middle finger to pinky, which is definitely not the same thing as the other way around. "TH" on millennium works fine for me.

Some letter-combinations that I think work particularly well on Millennium are words like "and", "note", "hold", "under", "test", "get", "starts" but even with M on pinky a word like "must" flows nicely.
Opinions may differ on this but it works for me!

## Word of warning

**Keyboard layouts are quite personal and my layouts make no ergonomic claims.**
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

Orderly ZXC (angle):
![Orderly ZXC](https://github.com/ijzerbroot/millennium/blob/main/orderly-zxc.png)

Orderly (angle):
![Orderly](https://github.com/ijzerbroot/millennium/blob/main/orderly.png)

Rest:
![Rest](https://github.com/ijzerbroot/millennium/blob/main/rest.png)


## Stats

I initially wanted to post detailed stats on the layouts but found that they are too dependent on analyzer-flavors and their configuration. The numbers might be misleading.
Overall all the above layouts have massively improved statistics compared to QWERTY, regardless of which analyzer you care to use. Feel free to try.

## In ASCII

Here are the layouts in copy-pasteable format:

Orderly
```
q , u f w  k d r l y  
a o e s c  m t n h i -
 x z g b j  p v / ; .  
```

Orderly ZXC
```
q , u g f  k d r l y  
a o e s w  m t n h i -
 z x c b j  p v / . ;
```

Millennium
```
m l d g w  q f o u ,  
h r t s y  p n a e i /
 z x k c v  j b ' ; .
```

Millennium Y
```
m l d g v  q f o u ,  
h r t s w  j n a e i /
 z x k c b  p y ' ; .  
```

Millennium Angle
```
m l d g v  q f o u ,  
h r t s y  p n a e i /
 x k c w z  j b ' ; .
```

Millennium Y Angle
```
m l d g v  q f o u ,  
h r t s b  j n a e i /
 x k c w z  p y ' ; .  
```

Rest
```
q y w m g ; f o u j
r e s t d b n a i l
 z x c v k p h , . /
```
```
