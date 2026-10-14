## Challenge

### Amplify the movement

Multiply the tilt so a small movement changes the sound a lot. Try different numbers instead of `2`.

```microbit
basic.forever(function () {
    SoftMelodies.setDensity(input.rotation(Rotation.Roll) * 2)
})
```

### Use a different tilt

Change `roll` to `pitch`, then tip the micro:bit forwards and backwards to change the rhythm.

```microbit
basic.forever(function () {
    SoftMelodies.setDensity(input.rotation(Rotation.Pitch))
})
```

### Change your shake

Use the drop-down menu in `on shake`{:class='microbitinput'} to choose a different movement, like `logo up`{:class='microbitinput'} or `screen down`{:class='microbitinput'}.

```microbit
input.onGesture(Gesture.LogoUp, function () {
    SoftMelodies.play(SoftMelodies.Melody.LiftOff)
})
```

[[[microbit-share]]]
