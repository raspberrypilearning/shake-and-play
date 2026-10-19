## Change the tempo

Use movement to change the tempo of your sound.

> [!TASK]
>
> From the `Basic`{:class='microbitbasic'} menu, drag a `forever`{:class='microbitbasic'} block into the code area.
>
> From the `Sounds`{:class='microbitserial'} menu, drag a `play`{:class='microbitserial'} block inside it.
>
> ![A forever block with a play block inside it, set to 0: spiral at tempo 120.](images/sounds-forever.png){:width="450px"}

**Test:** Listen to the simulator. The sound plays over and over.

> [!TASK]
>
> Click the drop-down menu in the `play`{:class='microbitserial'} block in the `forever`{:class='microbitbasic'} block and choose a sound for your loop.

> [!INFO]
>
> The **tempo** is how fast the sound plays. Lower numbers are slower, and higher numbers are faster.

> [!TASK]
>
> Experiment with the tempo in the `play`{:class='microbitserial'} block in the `forever`{:class='microbitbasic'} block. Try `60`, then try `120`.

> [!TIP]
>
> A tempo of `0` is silent.

**Test:** Listen to the simulator. The tempo changes.

Now let your movement choose the number.

> [!TASK]
>
> From the `Input...more`{:class='microbitinput'} menu, drag a `rotation (°) pitch`{:class='microbitinput'} block into the tempo number in the `play`{:class='microbitserial'} block.
>
> ![An animation of opening the Input...more menu and dragging a rotation block into the tempo number of the play block.](images/rotation-to-tempo.gif){:width="450px"}
>
> Change `pitch` to `roll`.
>
> ![A forever block containing a play block with rotation roll in its tempo input.](images/roll.png){:width="450px"}

> [!TIP]
>
> **Roll** is how far the micro:bit tips from side to side.

Your program should have these three parts. Your sounds and the tempo for `on shake`{:class='microbitinput'} can be different.

![An example program with volume set on start, a sound triggered on shake, and a forever loop using rotation roll.](images/full-programme.png){:width="450px"}

> [!TASK]
>
> Click **Download**.
>
> ![The Download button in the MakeCode editor.](images/download-button.png){:width="300px"}

**Test:** Tip the micro:bit to the side. Check the tempo changes.

> [!DEBUG]
>
> If nothing changes, check which way your micro:bit is facing. Try `pitch` instead of `roll`, or tip it the other way.
