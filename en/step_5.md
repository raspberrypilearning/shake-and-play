## Shake a sound

Pick your favourite sound, then add a short sound you can play whenever you like.

> [!TASK]
>
> Click the drop-down menu in the `play`{:class='microbitserial'} block in the `forever`{:class='microbitbasic'} block and choose your favourite sound.
>
> ![The drop-down menu in the play block, showing the six sounds.](images/choose-sound.png){:width="300px"}

**Test:** Your favourite sound plays over and over on the simulator.

> [!TASK]
>
> From the `Input`{:class='microbitinput'} menu, drag an `on shake`{:class='microbitinput'} block into the code area.
>
> ```microbit
> input.onGesture(Gesture.Shake, function () {
> })
> ```

> [!TASK]
>
> From the `Sounds`{:class='microbitserial'} menu, drag a `play`{:class='microbitserial'} block inside the `on shake`{:class='microbitinput'} block.
>
> ```microbit
> input.onGesture(Gesture.Shake, function () {
>     SoftMelodies.play(SoftMelodies.Melody.SeedAndSpiral, 120)
> })
> ```

> [!TASK]
>
> Click the drop-down menu in the `play`{:class='microbitserial'} block and choose your short sound.
>
> ![The drop-down menu in the play block inside on shake.](images/short-sound.png){:width="300px"}

**Test:** Click **SHAKE** on the simulator. Your short sound plays.

![The SHAKE button on the MakeCode simulator.](images/simulator-shake.png){:width="300px"}

> [!TASK]
>
> Plug in the USB cable and click **Download**.

> [!TASK]
>
> Hold the USB plug, not the cable, and gently pull it out of the micro:bit.

**Test:** Put on your instrument. Listen to your sound, then shake to play your short sound.
