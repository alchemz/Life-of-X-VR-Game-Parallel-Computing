# Life-of-X-VR-Game-Using-HTC-Vive
This is a vr game to let the user to experience a life or a insect/microorganism/chicken, and etc

## Steps
### 1. Life of a corn
make the corn growth process be animated.


## Reference:
a. https://www.raywenderlich.com/149239/htc-vive-tutorial-unity

b. https://www.raywenderlich.com/159552/advanced-vr-mechanics-unity-htc-vive-part-1

c. https://www.raywenderlich.com/159610/advanced-vr-mechanics-unity-htc-vive-part-2

d. http://lib.csdn.net/article/vr/63024

e. http://blog.csdn.net/kmyhy/article/details/76686208

f. http://blog.csdn.net/kmyhy/article/details/77483305

g. http://blog.csdn.net/kmyhy/article/details/77850747

I got inspired by the Game Of Life assignment a lot, and I am going to create a HTC Vive game with the cellular automation concept. 
- Make each entity of the system evolve automatically
- Use parallel computing algorithm to make the game run properly and fast

The game mechanics are the following:
- Build up a world with entities from different hierarchies, in other words, they have different power level, and belongs to different  food chain.
- Use vive headset to get the maximum immersive experience to this virtually world. For example, imagine that if you choose to born with a corn seed, you will experience the whole process of growth, being collected by the farmer, being transported to the market, being eaten by a human being, and etc.

Why Parallel computing is important?
- As a continuously running and evolving world, there could be race conditions for the multi-threading process
- From the starting point, the game could be simple with a small number of entities, yet as time is going, the game could be huge, and we need use parallel computing to make the program ruining in good condition.
