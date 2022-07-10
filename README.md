# Thought Process

Making the design, Different situations have been simulated and studied to further understand the factors that may affect the motion of the design.
For and easier approach, the different cases will be discussed one by one.

### Moving one Leg while the rest of the body is stationary
Basically the distance the robot can move without rotating the hip or using some help from the other leg

### Moving one leg with the help of the other leg
here, the motion was simulated as the previous case, but with the addition of ankle rotation from the other leg. ( Hip is still stationally)

### Motion with the help of the hip
Here, the support from the hip were allowed, but not from the other leg.

# Conclusions
Moving one leg without the help of the hip nor the other leg, distance traveled will be affected by the size of that leg ankle,(distance before the foot is lifted from the ground). And this is very important since the wheels will be installed there.

Having the support only from the other ankle will add up a forward motion, and that is equal to the size of the foot minus the size times cos(angle of lift). Note that this was not considered an option, since lifting the ankle of the other foot off ground, means lifting the wheel off ground.

Lastly, Rotating the hip can add up a forward motion to the leg, and its proportional to the angle of rotation, How ever, the hip rotating here is used to recover the front side of the first foot being lifted.

**Making the Calculations:**

distance Traveled: 13cm

Leg size: 59.234cm

using Tan Inverse,

Angle of movement: 12.378

**Here is my initial thought process:**


![IMG_7028](https://user-images.githubusercontent.com/109004035/178127757-d5f4758f-5040-4f94-9131-7bf97bbcdc55.jpg)


