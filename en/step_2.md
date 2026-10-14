## Play a sound

Make your instrument play a sound, and turn it on and off with the buttons.

> [!TASK]
>
> Open the starter project at [rpf.io/shake-and-play](https://rpf.io/shake-and-play){:target="_blank"}.

The starter project has a **sound library** called `Sounds`{:class='microbitfunctions'}. It has six short sounds for your instrument.

![The Sounds menu in MakeCode, showing its blocks.](images/synth-menu.png){:width="450px"}

> [!TASK]
>
> From the `Sounds`{:class='microbitfunctions'} menu, drag a `play`{:class='microbitfunctions'} block inside the `forever`{:class='microbitbasic'} block.
>
> ```microbit
> basic.forever(function () {
>     SoftMelodies.play(SoftMelodies.Melody.SeedAndSpiral)
> })
> ```

**Test:** Listen to the simulator. The sound plays over and over.

> [!TASK]
>
> Click the drop-down menu in the `play`{:class='microbitfunctions'} block and choose a different sound. Listen to all six.
>
> ![The drop-down menu in the play block, showing the six sounds.](images/choose-sound.png){:width="300px"}

Every instrument needs a way to go quiet, so you can leave a gap when you play with others.

> [!TASK]
>
> Add an `on button B pressed`{:class='microbitinput'} block from the `Input`{:class='microbitinput'} menu.
>
> From the `Music`{:class='microbitmusic'} menu, drag a `set volume`{:class='microbitmusic'} block inside it. Change the volume to `0`.
>
> ```microbit
> input.onButtonPressed(Button.B, function () {
>     music.setVolume(0)
> })
> ```

> [!TASK]
>
> Add an `on button A pressed`{:class='microbitinput'} block from the `Input`{:class='microbitinput'} menu.
>
> Drag another `set volume`{:class='microbitmusic'} block inside it. Change the volume to `255`.
>
> ```microbit
> input.onButtonPressed(Button.A, function () {
>     music.setVolume(255)
> })
> ```

> [!TASK]
>
> From the `Music`{:class='microbitmusic'} menu, drag a `set volume`{:class='microbitmusic'} block inside the `on start`{:class='microbitbasic'} block. Change the volume to `255`.
>
> ```microbit
> music.setVolume(255)
> ```

**Test:** Click **B** on the simulator to turn the sound off. Click **A** to turn it back on.
