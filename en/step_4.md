## Change the tempo

Use movement to change the tempo of your sound.

> [!TASK]
>
> From the `Sounds`{:class='microbitserial'} menu, drag a `play`{:class='microbitserial'} block inside the `forever`{:class='microbitbasic'} block.
>
> ![A forever block with a play block inside it, set to 0: spiral at tempo 120.](images/sounds-forever.png){:width="450px"}

**Test:** Listen to the simulator. The sound plays over and over.

> [!TASK]
>
> Click the drop-down menu in the `play`{:class='microbitserial'} block in the `forever`{:class='microbitbasic'} block and choose a sound for your loop.
>
> ![The drop-down menu in the play block, showing the six sounds.](images/choose-sound.png){:width="300px"}

> [!INFO]
>
> The **tempo** is how fast the sound plays. Lower numbers are slower, and higher numbers are faster.

> [!TASK]
>
> Experiment with the tempo in the `play`{:class='microbitserial'} block in the `forever`{:class='microbitbasic'} block. Try `60`, then try `120`.
>
> Add image

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
> add image
>

Add tip here -  to 


> [!TIP]
>
> **Roll**
>
> ![An animation of opening the Input...more menu and dragging a rotation block into the tempo number of the play block.](images/rotation-to-tempo.gif){:width="450px"}

> [!TASK]
>
> Plug in the USB cable and click **Download**.
>
> ![The Download button in the MakeCode editor.](images/download-button.png){:width="300px"}

> [!TASK]
>
> Hold the USB plug, not the cable, and gently pull it out of the micro:bit.

**Test:** Tip the micro:bit to the side. Check the tempo changes.

> [!DEBUG]
>
> If nothing changes, check which way your micro:bit is facing. Try `pitch` instead of `roll`, or tip it the other way.
