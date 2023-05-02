## IOS Watch Data

### Introduction
This repo is meant to share some data points for what the gyroscope and accelerometer look like while taking a few different putting swings (golf). The data is retrieved from [Apple's Core Motion](https://developer.apple.com/documentation/coremotion/cmmotionmanager) library. My goal is to share what I have learned about these APIs, along with the limitations.

### The Data

#### Normal Swing (Accelerometer)
![Accelerometer Data for normal swing](/assets/accelerometer-normal.png)
This is a normal golf swing putt for a right hander, with my watch on the left hand. This accelerometer uses 3 axes, so depending on the direction, one will always be more dominant the the others, unless you created motion perfectly dividing two axes. Consider this image ![this image](https://docs-assets.developer.apple.com/published/96e9d46b41/c9b606b2-9a52-487e-8385-e710ffa1ce5f.png). My left hand while putting a ball has my watch face mostly facing to my left, so the Z axes is the most dominant. It shows up as the most noisy on my follow through, as I swing my club from right to left. The other axes also move, but not as quickly.
#### Slow backswing, fast follow thru (Accelerometer)
![Accelerometer Data for slow take back and fast follow through](/assets/accelerometer-slowback-fastthru.png)
#### Normal swing and grip (Gyroscope)
![Gyroscope Data for normal swing](/assets/gyro-normal.png)
#### Normal swing and claw grip (Gyroscope)
![Gyroscope Data for normal grip](/assets/gyro-claw.png)
#### Bad swing and normal grip (Gyroscope)
![Gyroscope Data for bad swing](/assets/gyro-badswing.png)
