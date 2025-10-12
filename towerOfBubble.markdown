---
layout: default
title: TowerOfBubble
galleryImages:
- /assets/TowerOfBubbles/Image1.png
- /assets/TowerOfBubbles/Image2.png
- /assets/TowerOfBubbles/Image3.png
- /assets/TowerOfBubbles/Image4.png
- /assets/TowerOfBubbles/Image5.png
background: /assets/TowerOfBubbles/Background.png
overlay: light
fontColor: "#FFFFFF"
---
<section id="Tower of Bubble" markdown="1">
![Tower of Bubble]({{ '/assets/TowerOfBubbles/Name.png' | relative_url }})

### Engine: Unity Engine
### Teamsize: 8
### Timeframe: 48 Hours


{% include gallery.html 
    id="TowerOfBubble"
    images=page.galleryImages %}


## My work

### Physics

Built a custom physics system that calculates reactive propulsion forces when shooting bubbles. Carefully balanced force application, 
drag, and gravity to achieve smooth, controllable, and believable underwater motion.

### Input handeling

Implemented responsive input controls that allow precise aiming and shooting in any direction. Inputs directly influence 
propulsion force vectors, enabling intuitive and skill-based movement.

### Player movement

Designed a unique propulsion-only movement system with no traditional jumping or climbing. The shrimp’s trajectory and 
momentum depend entirely on bubble direction and firing rhythm, requiring continuous adjustment and precision.

### Obstacles and platforms 

Created interactive environments with static and dynamic hazards such as rotating saws and sea urchins. 
Platforms provide rest points and navigation challenges, while obstacle timing and placement encourage mastery of the propulsion mechanic.


#### [Game jam site](https://globalgamejam.org/games/2025/tower-bubble-6)


#### [Game download](https://ggjv4.s3.us-west-1.amazonaws.com/files/games/2025/60556/exec/TowerOfBubble.zip?VersionId=GyD2QRuTN7JitHn65uPWjq6i0t2BtJkZ)


</section>