# Arduino hacks and fun

## Makershield test

Fork from syrnick/arduino to make use of http://makezine.com/projects/makershield-tutorial/. thanks Alexander

### Code

    makershield_tdd/makershield_tdd.ino

### Setup

Connect all makershield parts to arduino:

 * POT to A1
 * LED1 to D6
 * LED2 to D7
 * BTN1 to D0
 * Set Jumper to 3.3V

### Behavior

Hold the button (BTN1) for 1 second to turn it ON or OFF. When OFF,
all LEDs will be off. When ON, the LED1 is always on, LED2 brightness
reflects the pot. The update rate is 10 Hz, but it's easy to change.
