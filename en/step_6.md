## Add a short sound

Give your instrument a short sound you can play whenever you like.

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
> From the `Sounds`{:class='microbitfunctions'} menu, drag a `play`{:class='microbitfunctions'} block inside the `on shake`{:class='microbitinput'} block.
>
> ```microbit
> input.onGesture(Gesture.Shake, function () {
>     SoftMelodies.play(SoftMelodies.Melody.SeedAndSpiral)
> })
> ```

> [!TASK]
>
> Click the drop-down menu in the `play`{:class='microbitfunctions'} block and choose your short sound.
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

**Test:** Put on your instrument and shake it. Your short sound plays.
