# py-kivy-pong
Completed [kivy pong tutorial](https://kivy.org/doc/stable/tutorials/pong.html)

### Updates from tutorial:
* Player1 can move paddle with 'w' and 's' keys
* Player2 can move paddle with 'up' and 'down' arrow keys
* Hit counter for how many hits between paddles between serves
* Ball stops accelerating once overall velocity is > 25

### TODO:
* Pause game option
* Declare winner

### Bugs Resolved
| Issue       | Bug         | Fix         |
| ----------- | ----------- | ----------- |
| After about 25 paddle hits - player2 automatically wins | velocity > paddle width causing ball to move out of bounds before collision with paddle was updated | Added max speed      |
