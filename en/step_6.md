## Change the tempo

Use movement to change the tempo of your sound.

> [!INFO]
>
> The **tempo** is how fast the sound plays. Lower numbers are slower, and higher numbers are faster.

> [!TASK]
>
> Experiment with the tempo in the `play`{:class='microbitserial'} block in the `forever`{:class='microbitbasic'} block. Try `60`, then try `120`.
>
> ```microbit
> basic.forever(function () {
>     SoftMelodies.play(SoftMelodies.Melody.SeedAndSpiral, 60)
> })
> ```

> [!TIP]
>
> A tempo of `0` is silent.

**Test:** Listen to the simulator. The tempo changes.

Now let your movement choose the number.

> [!TASK]
>
> From the `Input...more`{:class='microbitinput'} menu, drag a `rotation (°) pitch`{:class='microbitinput'} block into the tempo number in the `play`{:class='microbitserial'} block.
>
> Change `pitch` to `roll`.
>
> ```microbit
> basic.forever(function () {
>     SoftMelodies.play(SoftMelodies.Melody.SeedAndSpiral, input.rotation(Rotation.Roll))
> })
> ```
>
> ![An animation of opening the Input...more menu and dragging a rotation block into the tempo number of the play block.](images/rotation-to-tempo.gif){:width="450px"}

> [!TIP]
>
> **Roll** is how far the micro:bit tips from side to side.

> [!TASK]
>
> Plug in the USB cable and click **Download**.

> [!TASK]
>
> Hold the USB plug, not the cable, and gently pull it out of the micro:bit.

**Test:** Put on your instrument. Press **A**, then slowly twist your wrist to tip the micro:bit to the right. The tempo gets faster. Twist back to make it slower, until it goes silent.

> [!DEBUG]
>
> If nothing changes, check which way your micro:bit is facing. Try `pitch` instead of `roll`, or tip it the other way.
