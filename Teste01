let umidade = 0
input.onButtonPressed(Button.A, function () {
    basic.showNumber(pins.analogReadPin(AnalogPin.P1))
})
basic.forever(function () {
    umidade = pins.analogReadPin(AnalogPin.P1)
    if (umidade > 1000) {
        basic.showIcon(IconNames.Square)
    } else if (umidade > 800) {
        basic.showIcon(IconNames.Happy)
    } else {
        basic.showIcon(IconNames.Sad)
    }
})
