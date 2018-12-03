What does an engineer do when he needs to paint his house?  He builds a robot to do it for him.  

The robot consists of a beam, say 20 feet long, servo positioned trolly that rides on said beam that incorporates a servo hoist which positions a paint sprayer in the gravity direction.  

For a couple of reasons, not the least of which is induced oscillation, the paint bot paints in vertical passes. But horizontal passes may be preferred.  How to you make the paint head have nice controlled motion when you are reversing the trolly at the end of each pass?

Right now, the status of this project is that I've started to write an environment where I can use a ML agent to teach it self to drive the trolly in such a way that the paint head doesn't oscillate out of control and in fact has nice constant velocity when not reversing direction.  The real deal would almost certainly need inertial feedback on the paint head.  Right now, the horizontal motion is just an academic exercise, but I plan on building the paint bot.

 