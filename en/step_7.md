## Challenges

### Amplify the movement

Multiply the tilt so a small movement changes the tempo a lot, and the tempo can go faster than normal. Try different numbers instead of `2`.

```microbit
input.rotation(Rotation.Roll) * 2
```

### Use a different tilt

Change `roll` to `pitch`, then tip the micro:bit forwards and backwards to change the tempo.

```microbit
input.rotation(Rotation.Pitch)
```

### Try a different sensor

Put a different sensor in the tempo, like `acceleration (mg) x`{:class='microbitinput'} or `light level`{:class='microbitinput'}. With acceleration, try `y` and `z` too.

```microbit
input.acceleration(Dimension.X)
```

### Change your shake

Use the drop-down menu in `on shake`{:class='microbitinput'} to choose a different movement, like `logo up`{:class='microbitinput'} or `screen down`{:class='microbitinput'}.

### Make your own sound

Use the `play melody`{:class='microbitmusic'} block from the `Music`{:class='microbitmusic'} menu. Click the melody to open the editor and make your own sound, then put the block in your `on shake`{:class='microbitinput'} block.

![The melody editor open below a play melody block inside on shake. Choose squares to change the notes, then click Done.](images/melody.png){:width="450px"}

```microbit
input.onGesture(Gesture.Shake, function () {
    music.play(music.stringPlayable("- - - - - - - - ", 120), music.PlaybackMode.UntilDone)
})
```

### Meet the MiMu gloves

Musicians wear MiMu gloves to make music with the movement of their hands. Find out more at [mimugloves.com](https://mimugloves.com){:target="_blank"}.

[[[microbit-share]]]
