# Pipeline-in-VHDL
This project implements a simple pipeline in VHDL 

Implemented a simple pipelined circuit. The circuit will utilize one
32-bit block RAM to continually provide 4 8-bit inputs per cycle, and one 17-bit block
RAM to store an output each cycle. In software, transfer data has been initialized from the
microprocessor into the input block RAM, with the size of the input specified, started the circuit,
and then waited for completion, at which point the software reads data from the output
blockRAM and output it to the screen.
