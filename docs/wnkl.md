# Wankel Engine Design
Well wankel engines have been interesting because they look so cool. They dont look like any other engine i've ever seen. no reciprocating members, no valves, yet is 4 stroke and doesn't need crankcase induction. Looks space age. SO SPACE AGE. So I tried designing one.

## Step One: Figure out the geometry
Well I figured out the shape of the chamber was a epitrochoid. Now what is an epitrochoid? Math speak for a deformed packing peanut? No? A little bit of googling led me to this:
![THIS is an epitrochoid](https://raw.githubusercontent.com/GrouchySmoke/GrouchySmoke.github.io/main/docs/assets/epitrochoid.png)
Now this obviously doesnt look right. This has got 3 lobes while the wankel chamber ought to be 2 lobes. The ratio between the central circle and planet circle determines the number of lobes. So for 2 lobes the diameter of the central circle is to be twice the diameter of the planetary circle.
![better Epitrochoid](https://raw.githubusercontent.com/GrouchySmoke/GrouchySmoke.github.io/main/docs/assets/wnkl.png)
That looks much better. Now that ive gotten the base theory, I drew up the housing in a crude but effective manner. The way it was done is not the best way, not with actual funstion but by emulating the actual behaviour of the plantary circle and connecting the discrete points with a spline.
![Housing](https://raw.githubusercontent.com/GrouchySmoke/GrouchySmoke.github.io/main/docs/assets/housing.png)
The model is parametrised, with only a base variable, the central circle that need to be edited for different sizes.
