## Shake a sound

Pick a sound and play it with a shake.

> [!TASK]
>
> Open the starter project at [rpf.io/shake-starter](https://rpf.io/shake-starter){:target="_blank"}.

> [!TASK]
>
> Click **Edit Code**.
>
> ![The starter project page with a red circle around the Edit Code button at the top right.](images/edit-code.png){:width="450px"}

> [!TASK]
>
> Choose From the `on shake`{:class='microbitinput'} block from the `Input`{:class='microbitinput'} menu, and drag into the code area.
>
> ```microbit
> input.onGesture(Gesture.Shake, function () {
> })
> ```

The starter project has a **custom menu** called `Sounds`{:class='microbitserial'}. It has twelve sounds for you to use.

![The MakeCode menu with the Sounds category.](images/sounds-menu.png){:width="200px"}

> [!TASK]
>
> From the `Sounds`{:class='microbitserial'} menu, drag a `play`{:class='microbitserial'} block inside.
>
> ![An on shake block with a play block inside it, set to 0: spiral at tempo 120.](images/sounds-shake.png){:width="450px"}

> [!TASK]
>
> Click the drop-down menu to choose a sound. Scroll down to see all twelve.
>
> ![The drop-down menu in the play block. Scroll down to see all twelve sounds.](images/drop-down.png){:width="450px"}

**Test:** Click **SHAKE** on the simulator and check that your sound plays.

![The SHAKE button on the MakeCode simulator.](images/shake-sim.png){:width="300px"}

> [!TASK]
>
> If the sound is quiet you can turn the volume up.
>
> From the `Music`{:class='microbitmusic'} menu, drag a `set volume`{:class='microbitmusic'} block inside `on start`{:class='microbitbasic'}. Change the volume to `255`.
>
> ```microbit
> music.setVolume(255)
> ```

