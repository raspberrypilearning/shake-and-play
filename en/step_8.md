## Challenges

### Amplify the movement

Multiply the tilt so a small movement changes the tempo a lot, and the tempo can go faster than normal. Try different numbers instead of `2`.

```microbit
basic.forever(function () {
    SoftMelodies.play(SoftMelodies.Melody.SeedAndSpiral, input.rotation(Rotation.Roll) * 2)
})
```

### Use a different tilt

Change `roll` to `pitch`, then tip the micro:bit forwards and backwards to change the tempo.

```microbit
basic.forever(function () {
    SoftMelodies.play(SoftMelodies.Melody.SeedAndSpiral, input.rotation(Rotation.Pitch))
})
```

### Change your shake

Use the drop-down menu in `on shake`{:class='microbitinput'} to choose a different movement, like `logo up`{:class='microbitinput'} or `screen down`{:class='microbitinput'}.

```microbit
input.onGesture(Gesture.LogoUp, function () {
    SoftMelodies.play(SoftMelodies.Melody.LiftOff, 120)
})
```

### Make your own sound

Use the `play melody`{:class='microbitmusic'} block from the `Music`{:class='microbitmusic'} menu. Click the melody to open the editor and make your own sound, then put the block in your `on shake`{:class='microbitinput'} block.

```microbit
input.onGesture(Gesture.Shake, function () {
    music.play(music.stringPlayable("- - - - - - - - ", 120), music.PlaybackMode.UntilDone)
})
```

[[[microbit-share]]]
