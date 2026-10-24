# Guitar Stomp-Box Stomp-Switch Wiring
Copyright © 2021 Bart Massey

## Circuit

<img src="stompbox.png" width=1170>

No modern stomp box would be without a stomp switch to
provide a bypass capability. This switch is
also used as a power switch. The "true bypass" wiring shown
here completely removes the circuit when in the bypass
("off") position.

With this wiring plan, the device will be powered off and in
"true bypass" (wire from input to output) unless an
instrument is plugged into it *and* the stomp switch is set
to use the effect. When the effect is active, power will be
drawn from the external 9V center-negative supply if plugged
in, else from the internal 9V battery. Thus, for the battery
to drain, the 9V supply must be unplugged, the input must be
plugged in, and the foot switch must be set to effect mode.

There is some talk in the literature about "anti-pop"
capacitors, but I haven't understood the details. Perhaps I
will need to rework the wiring of this switch, but it should
be good enough to start.

## Working With This Circuit

You will need [KiCad](https://kicad.org/) version 5.1 or better. I am
using Debian Linux KiCad `5.1.9+dfsg1-1`. The `stompbox.pro`
file should just work.

## License

This work is licensed under the "MIT License".  Please see
the file `LICENSE` in this distribution for license terms.
