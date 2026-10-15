## Change the tempo

Use movement to change the tempo of your sound.

> [!INFO]
>
> The **tempo** is how fast the sound plays. Lower numbers are slower, and a very low number is silent. Higher numbers are faster.

> [!TASK]
>
> Change the `120` in the `play`{:class='microbitserial'} block in the `forever`{:class='microbitbasic'} block to `0`.
>
> ```microbit
> basic.forever(function () {
>     SoftMelodies.play(SoftMelodies.Melody.SeedAndSpiral, 0)
> })
> ```

**Test:** Listen to the simulator. Your sound is silent.

> [!TASK]
>
> Change `0` to `60`.

**Test:** Listen to the slow tempo.

> [!TASK]
>
> Change `60` to `200`.

**Test:** Listen to the fast tempo.

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
