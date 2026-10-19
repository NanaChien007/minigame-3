# MG3
## Devlog

1. The defult value for float is 0.0, an int is 0, a bool is false, and a string is null. 

2. The update () method is automatically called by Unity once every frame when the script is active and enabled. We don't need to manually call it because Unity handles it for us. This time, we use Update () to keep track of the timer by subtracting Time. deltaTime every frame

3. TimerText class uses the timer to keep track of how much time the player has left in the game. When the game starts, it calls BeginTimer(0 to start the countdown. The Update () method checks every frame whether the timer has finished by calling IsFinished(). If the time runs out, it calls GameOver (). It also updates the timer text on the screen using GetTimeLeft () so the player can see how much time is remaining.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)