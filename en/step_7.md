## Shape your sound

Use movement to change how your sound plays.

> [!INFO]
>
> You can change the **rhythm** of the sounds. Lower numbers make a simple rhythm, and 0 is silent. Higher numbers make a busy rhythm.

> [!TASK]
>
> From the `Basic`{:class='microbitbasic'} menu, drag a second `forever`{:class='microbitbasic'} block into the code area.

> [!TASK]
>
> From the `Sounds`{:class='microbitfunctions'} menu, drag a `set rhythm to 50`{:class='microbitfunctions'} block inside the new `forever`{:class='microbitbasic'} block.
>
> ```microbit
> basic.forever(function () {
>     SoftMelodies.play(SoftMelodies.Melody.SeedAndSpiral)
> })
> basic.forever(function () {
>     SoftMelodies.setDensity(50)
> })
> ```

> [!TASK]
>
> Change `50` to `0`.

**Test:** Listen to the simulator. Your sound is silent.

> [!TASK]
>
> Change `0` to `20`.

**Test:** Listen to the simple rhythm.

> [!TASK]
>
> Change `20` to `100`.

**Test:** Listen to the busy rhythm.

Now let your movement choose the number.

> [!TASK]
>
> From the `Input...more`{:class='microbitinput'} menu, drag a `rotation (°) pitch`{:class='microbitinput'} block into the number in `set rhythm to`{:class='microbitfunctions'}.
>
> Change `pitch` to `roll`.
>
> ```microbit
> basic.forever(function () {
>     SoftMelodies.play(SoftMelodies.Melody.SeedAndSpiral)
> })
> basic.forever(function () {
>     SoftMelodies.setDensity(input.rotation(Rotation.Roll))
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

**Test:** Put on your instrument. Press **A**, then slowly twist your wrist to tip the micro:bit to the right. The rhythm gets busy. Twist back to make it simple again.

> [!DEBUG]
>
> If nothing changes, check which way your micro:bit is facing. Try `pitch` instead of `roll`, or tip it the other way.

