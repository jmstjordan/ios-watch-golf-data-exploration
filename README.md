## IOS Watch Data

### Introduction
This repo is meant to share some data points for what the gyroscope and accelerometer look like while taking a few different putting swings (golf). The data is retrieved from [Apple's Core Motion](https://developer.apple.com/documentation/coremotion/cmmotionmanager) library.

### The Data

#### Normal Swing (Accelerometer)
![Accelerometer Data for normal swing](/assets/accelerometer-normal.png)
This is a normal golf swing putt for a right hander, with my watch on the left hand.
#### Slow backswing, fast follow thru (Accelerometer)
![Accelerometer Data for slow take back and fast follow through](/assets/accelerometer-slowback-fastthru.png)
This is the same swing path and setup, except I take the club back slowly, and accelerate quickly through.
#### Normal swing and grip (Gyroscope)
![Gyroscope Data for normal swing](/assets/gyro-normal.png)
This is the same swing path with a normal swing speed, except we are plotting the gyroscope data.
#### Normal swing and claw grip (Gyroscope)
![Gyroscope Data for normal grip](/assets/gyro-claw.png)
This is the same swing path and setup, except we are using a claw grip.
#### Bad swing and normal grip (Gyroscope)
![Gyroscope Data for bad swing](/assets/gyro-badswing.png)
This is a normal swing setup, except we are making obvious pathing mistake with wrist turns.