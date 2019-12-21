# Benjolin

CC-By-NC 4.0, 2019

SMT Benjolin. Strictly for non-commercial use.

- - - -

This is a SMT version of the Benjolin with some modifications to power supply and protection.

Built and verified, Oct 2019

Rob Hordijk (the designer of the Benjolin) has kindly given permission Oct 27, 2019) for this to be shared on GitHub with the proviso that these files cannot be used by third parties for commercial use.

If you make changes and want to republish, please contact Rob before doing so!

- - - -

![Benjolin](https://github.com/forestcaver/Benjolin/blob/master/569-modular_benjolin.jpg)

- - - -

## v1.0 ##

Files: Eagle pcb board, Eagle pcb schematic, Gerber files for the pcb, Eagle panel board, Gerber files for the panel (I use one-sided aluminium pcb with no copper), 2x images of the finished module

I used a combination of Kweiwen's schematic on his github as well as the electro-music schematics. I then added the power supply and protection.

The main issue (which is an original feature) for me is that the output volume is quite low. This is true of the original design. You can adjust one of the resistors just before the filter to boost the gain. But this can cause subtle distortion in the filter. If I ever revise the board I’ll add an output gain cell. It doesnt bother me much on this version - but just be aware of it....

- - - -

## v1.6 ##

This version adds an opamp to add gain to the output to approx 10v p-p. It also normalises T1 to osc 2 cv input
(can still be attenuated with the pot), normalises T2 to osc 1 cv and T2 to filter cv input.

Please note: I have not built this version. I built a version that had a trivially small error, so I updated the design before uploading here. I am confident it will be fine but I have not 100% verified it!
