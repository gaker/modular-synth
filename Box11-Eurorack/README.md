# Box11 Eurorack

I love synthesizers.com modules. I also love eurorack modules This is an attempt to marry the two using a full-width faceplate to house 3U 
modules, as well as add in some other goodies.

I've gone with the [Box11 system](https://shop.synthesizers.com/products/qcb11) for all of my DotCom modules, and want to integrate those into eurorack. I've been rocking with the 64HP moog skiffs, they are full, so it is time to do something else.

The following gives me 104hp of eurorack space in a synthesizers.com Box 11 frame. With about 1.5U or so of space, I decided to go all in and have fun taking up the space.

## Faceplate

Status: in progress.

## Utilities

With ~1.5U of space just sitting there begging to have cables and modules
attached, I would be remiss if I didn't take advantage of all of this 
real estate.   

### 1/4" to 1/8" passive passthrough

* Switchcraft [35rm3s](https://www.switchcraft.com/3-5mm-stereo-jack-rear-mount-locking-sealed-rohs/35rm3s/) 1/8" Jacks
* Switchcraft [112ax](https://www.switchcraft.com/single-closed-circuit-solder-lug-termination/112ax/) 1/4" Jacks

### Fork

Simple 1 -> 3 (x2) buffered mults.

Power in:

    * +12V
    * -12V
    * GND

Via a [TE 640456-3](https://www.mouser.com/ProductDetail/571-6404563) from the Oscillator.

### Voice

VCO built on the [AS3340](https://www.alfarzpp.lv/eng/sc/AS3340.pdf) Oscillator.

### Sway

3x Attack/Release Envelope generators.
Gate one is normalized to gate 2

### Tone

VCF built on the [AS3320](https://www.alfarzpp.lv/eng/sc/AS3320.pdf)

### AMP

VCA built on the [AS3360](https://www.alfarzpp.lv/eng/sc/AS3360.pdf).
Powers two Hairball Audio 8045 VU Meters.
