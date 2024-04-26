# jzha0529-9103_Quiz-8



## Imaging Technique Inspiration


__Halo (halation) effect__ is a more commonly used imaging technology in digital artworks, it can wrap an object with light to emphasize the visual impact of the object, or shroud the scene with light to show a hazy sense of contrast with other scenes.


__Examples:__

![Imaging example](assets/image1.jpg)


![Imaging example](assets/image2.jpg)


In my project, I can use similar techniques to wrap an object or part of an object with light, or to blur a distant scene with light, both of which can be used in the artwork __'Wheels of fortune'__ and, __'Saint Georges majeur au cre?puscule'__ respectively.





## Coding Technique Exploration


__In Unity (C sharp)__, I found an example of implementing a halo effect on an object:


![Imaging example](assets/image4.gif)


In this example, through one of the author's scripts, I learned that the author:

1. Directly use __SpriteGlowEffect__ to implement a glow effect on the obejct.
2. Setting random colors.
3. Setting the random color range.


in my p5.js project, I'm not sure p5 has a similar function, maybe I can try to create a circle of random color and vary the size and place it behind an object to achieve a similar effect.


> The script link: [Script Link](https://github.com/elringus/sprite-glow/blob/main/Assets/Scripts/GlowColorRandomizer.cs)
>