# Regfile
The regfile was designed by designing 32 bit registers from d-flip-flops first. Then, 32 of these registers were laid down and a decoder using a bit shifter was implemented to select a write register and 2 arrays of 32 tri state buffers were used to select read register 1 and 2. There are no known bugs.