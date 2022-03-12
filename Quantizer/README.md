# Quantizer

<img src="https://raw.githubusercontent.com/PierreIsCoding/sdiy/main/Quantizer/images/labels.jpg" height="500" /><img src="https://raw.githubusercontent.com/PierreIsCoding/sdiy/main/Quantizer/images/20220312_134829.jpg" height="500" />     

Another Quantizer? Yes! This project represents a powerfull, precize and flexible quantizer with not so many components in 6HP wide. It lets you quantize cv-levels with a 16-bit pwm based DAC using only two pins and the internal timers of an Arduino Nano. Musically it really can change your game. So why not build this one for yourself?

## Features
- Quantizes incomming cv signals to 7 scales, 4 triades or octaves, with a 16-bit precision output.
- Trigger output. Every time an incomming cv-signal gets quantized to a new signal the trigger out sends a pulse for external envelope generators etc.
- A "Sample and Hold" mode. When a jack is inserted into the clock input the device goes automatically into S&H mode. In this mode the quantizer only outputs a new quantized value after receiving the next clock pulse.
- Add glide to the output cv.
- Change on the fly how the module receives bipolar and unipolar input cv-signals.
- The leds represent piano keys.
- 

## Files
- Files for etching this project on a single board and single layer.
- The code for an Arduino Nano.
- Front panel dimensions.
- File for labels....updated soon.

## How to use it; example 1 (LFO)
- Connect the output cv with the 1V/oct of your favourite VCO.
- Insert a bipolar LFO into the cv-in of the module.
- Press the UP and DOWN buttons together. Now the module goes into bipolar mode.
- Change the scale by keep pressing the SCALE button while tapping either the UP ow DOWN buttons

## How to use it; example 2 (sequencer)
- Connect the output cv with the 1V/oct of your favourite VCO.
- Insert a cv-sequencer into the cv-in of the module.
- The module is in unipolar mode by default. If it is not press the UP and DOWN buttons together again.
- Check if the lowest led is on. This led represents a C-note. Tune your VCO accordingly.
- Change the scale by keep pressing the SCALE button while tapping either the UP ow DOWN buttons.
- Transpose the output by keep pressing the TRANSPOSE button while tapping either the UP ow DOWN buttons.

## How to use it; example 3 (sample and hold)
- Connect the output cv with the 1V/oct of your favourite VCO.
- insert a clock signal into the clock-input.
- insert a noise source into the cv-in.
- Press the UP and DOWN buttons together. Now the module goes into bipolar mode
- Change the scale by keep pressing the scale button while tapping either the UP ow DOWN buttons.
- Connect the output trigger to an envelope generator which opens and closes the VCO signal.


# Buildnotes

<img src="https://raw.githubusercontent.com/PierreIsCoding/sdiy/main/Quantizer/images/20220312_135047.jpg" height="500" />
<img src="https://raw.githubusercontent.com/PierreIsCoding/sdiy/main/Quantizer/images/20220312_135254.jpg" height="500" />
<img src="https://raw.githubusercontent.com/PierreIsCoding/sdiy/main/Quantizer/images/20220312_135047.jpg" height="500" />
<img src="https://raw.githubusercontent.com/PierreIsCoding/sdiy/main/Quantizer/images/20220312_135308.jpg" height="500" />
<img src="https://raw.githubusercontent.com/PierreIsCoding/sdiy/main/Quantizer/images/cut.jpg" height="500" />
<img src="https://raw.githubusercontent.com/PierreIsCoding/sdiy/main/Quantizer/images/tri_state.PNG" height="500" />