## CSE 167 HW4 Extra Credit
For extra credit, I implemented Monte Carlo path tracing. Since I didn't write acceleration, I removed all spheres from scene6 to make it run faster. Here is the comparison. 

The original scene6 image:

![scene6-original.png](https://raw.githubusercontent.com/GuangyanCai/CSE-167-HW4-extra-credit/master/scene6-original.png "scene6-original.png")

The Monte Carlo path traced scene6 image:

![scene6-mc.png](https://raw.githubusercontent.com/GuangyanCai/CSE-167-HW4-extra-credit/master/scene6-mc.png "scene6-mc.png")

Let's focus on the cuboid on the left.

The original scene6 image:

<img width="400" alt="scene6-original-1.png" src="https://raw.githubusercontent.com/GuangyanCai/CSE-167-HW4-extra-credit/master/scene6-original-1.png">

The Monte Carlo path traced scene6 image:

<img width="400" alt="scene6-mc-1.png" src="https://raw.githubusercontent.com/GuangyanCai/CSE-167-HW4-extra-credit/master/scene6-mc-1.png">

You can notice:
* The color bleed from the red wall on the left and the green wall on the right.
* The anti-aliasing effect at the edges of the cuboid.
