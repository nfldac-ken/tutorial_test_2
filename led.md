#Led tutorial_test_2

Text on opening

## Toggle and LED test of change 1

First Step

Drag the code to toggle the LED

```blocks
basic.forever(function () {
    led.toggle(0, 0)
})
```


## All the MakeCode

Second Step

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), randint(0, 4))
})
```