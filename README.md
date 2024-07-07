# Design Experiments 2 (Commit:  94480e3f465199bb50ac5fbfaebfc80805b37aed)
Tried:
1. Adding more to the combo vinyl setup (take B) to try and see if more circut vinyl = more stickiness.
2. Added support to the take A design because of when it gets hot, the new vinyl does not stay rigid, like the cricut design before it.

# Design Experiments with New Material (Commit: 5db087a183cfb1a76abdf685e50ab6e04ff7c582)
New material: https://www.amazon.com/dp/B073TVRQ5D?th=1

Tried three takes:
1. Having solely the new vinyl with the older shape and older vinyl covers. Handle is cricut vinyl. Take A shapes.
2. Have the new vinyl with the vinyl light cover pieces covered in low tack adhesive (https://www.amazon.com/3M-Spray-Artists-Adhesive-MMM6065/dp/B00006IFBF/ref=sr_1_9?keywords=low+tack+adhesive). Take A shapes.
3. Have the new vinyl with the non-sprayed vinyl light cover pieces and the cricut vinyl underneath to help with better adhesion. One specific weird shape (to be iterated on in next commit). Take B shapes.

# Design 3/4 (Commit: ceebccc8e51e03b29c95d98af19cea03b6045ae0)

Pros:
- Put the vinyl and window cling layers together so there's no drama getting them joined for the top (combination required 301 pressure)
- Has full sun block
- Seems to stick okay

Cons:
- Not as sticky as Design 2

# Design 2 (Commit: b0d6043b78d63c9f1fbc64f3df2b890bc0833a25)

Pros:
- Did cut well and fast
- Peeled off well and laid much more flat with a quick rolling motion of my wrist.

Cons:
- Multi pieces
- The vinyl piece was thin and broke when weeding
- The strap is so long that the ends stick to the window sometimes
- The strap feels like it'll break off. Not sure if that's a problem or not.
- Too thin. The sun shines straight through it.

# Design 1 (Commit: a7ae7d1d62f600c032e3408b9306f1db0db2ba78)

Pros:
- Did cut out well
- The black window cling seemed to handle okay

Cons:
- The corners fold in, the math for design 1 didn't fully work
- The peel off/on was hard
- Getting the cling to go on smoothly and quickly was not ideal.

# Math

((1/4*c^2) + (n^2))/(2n) = r
where:
- c is the chord length (or length of car block
- n is the height of the handle
- r is the radius of the circle (just here to find the length of the handle)

then

a = atan((1/2c)/(r-n))
- a is the angle between the chord and the vertical radius for n (see pic)

x = ar/180

Hence, with a diagonal width of (150^2) + (100^2) = width^2, then:
- c = 180.3mm

Wolfram input:
c=180.3; n=40; ((1/4*c^2) + (n^2))/(2*n)
https://www.wolframalpha.com/input?i=c%3D200.3%3B+n%3D40%3B+%28%281%2F4*c%5E2%29+%2B+%28n%5E2%29%29%2F%282*n%29
Result: 121.6mm

Then, I want to add 10mm+7mm to get through the attachment holes, then 20mm to get to an attachment point. Multiply this by 2 for both ends.

