# Dragon Gunship Avionics
I recently built a crude version of the dragon gunship from James Cameron's avatar. Quadracopter with many turrets, and very large weight. Due to its size, its pretty hard to control, especially with tiltrotors, so this project seeks to provide avionics control systems to make operations easier.

### The goals of this system are as follows:
* [] Provide stable transition from hovering to hovering to forward flight, and vice versa
* [] create emergency systems to automatically re-orient thrusters and ship during descents
* [] emergency system to compensate if 1 or 2 thrusters are knocked out
* [] effective turning during both hovering and level flight
* [] automated landing sequence to simplify landing
* [] emergency system to land when fuel is critically low
* [] loitering capability to set a periodic course around a ground target for extended fire support
* [] auto-pilot with GPS waypoints
* [] automatic compensation for environmental conditions in all above components (gravity on different planets, air resistance, thrust force, etc)