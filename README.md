# esphome example for Athom 2 button sw032us touch switch

Features:
* Impliments all features of the switch (wifi led, touch buttons, leds on touch buttons)
* The leds on the buttons can either be red or blue depending on if GPIO is high or low (only one gpio pin per red & blue led). The athom tasmota firmware had them red when on and blue when off but I inverted that. You can easily modify that though.
* configured red/blue leds on buttons as pwm outputs so that they fade between red & blue when button pressed
