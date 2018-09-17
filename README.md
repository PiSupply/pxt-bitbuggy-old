
# Bit:Buggy Software Package

Pi Supply [Bit:Buggy](https://www.pi-supply.com) car is a DIY smart car based around the BBC micro:bit. Bit:Buggy has 3 extended GPIO ports - two for driving servos and one for any other stuff! The basic version of the Bit:Buggy can perform functions such as line following, remote control and others. By adding some different sensors and modules you can extend the functionality to enable things like light following, obstacle avoidance, drawing and more.

![](https://github.com/PiSupply/pxt-bitbuggy/blob/master/icon.png?raw=true)

This software is forked from the ElecFreaks Ring:bit Car [package](https://github.com/elecfreaks/pxt-ringbitcar) which was developed by [ElecFreaks](https://www.elecfreaks.com/) with minor assistance from [Tinkercademy](https://tinkercademy.com/).

## User Guide
[Bit:Buggy User Guide](https://www.pi-supply.com)

## Code Example
```JavaScript
basic.forever(() => {
    BitBuggy.forward()
    basic.pause(1000)
    BitBuggy.turnleft()
    basic.pause(1000)
    BitBuggy.turnleft()
    basic.pause(1000)
    BitBuggy.back()
    basic.pause(2000)
})
```

## License
MIT

## Supported targets
for PXT/microbit (The metadata above is needed for package search.)
