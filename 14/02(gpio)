14/02/2024 -(GPIO-general purpose input output)

1.GPIO is used to : reading digital signals, issuing interrupts, generating triggers for external components

 2.GPIO pin - value consists of one of two voltage settings(high or low)
    GPIO port - grouping of GPIO pins(16pins)

3.high impedence state:
                       1. after reset MCU defalut GPIO pins are input mode.
                       2.GPIO pins will be in hight Z state or floating issuse
                       3.neither high or ground state

4.GPIO input mode with pull-up and pull-down state
                       1.internal pull down
                       2.internal pull up

5,GPIO output mode with open drain state::
           1.output configuration
           2. top of PMOS transistor is deactivated
           3.transistor is on. the pin pulled to the ground
           4.transistor is off. the drain of transistor will be floating open
           5. it has two states - ground,floats

6.Activating internal pull-up or external pull-down resistor


7.GPIO push,pull state:
                   1.default configuration of any GPIO pin in output mode
                   2.GPIO port by default,its pin will be  input mode
                   3.if you set any pin,its pin will be output mode
                   4.default - push-pull configuration
                   5.output will be pulled actively between low and high
                   6.push-pull - doesn't need any pull up/pull down resistor
                   7.out put the appropriate level
