# Design 2 (Commit: b0d6043b78d63c9f1fbc64f3df2b890bc0833a25)

Pros:
- Did cut well and fast
- Peeled off well and laid much more flat with a quick rolling motion of my wrist.

Cons:
- Multi pieces
- The vinyl piece was thin and broke when weeding
- The strap is so long that the ends stick to the window sometimes
- The strap feels like it'll break off. Not sure if that's a problem or not.

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

