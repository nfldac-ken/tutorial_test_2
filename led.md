#Led tutorial_test_2

## Toggle and LED

Drag the code to toggle the LED

```blocks
basic.forever(function () {
    led.toggle(0, 0)
})
```


## All the MakeCode

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), randint(0, 4))
})
```