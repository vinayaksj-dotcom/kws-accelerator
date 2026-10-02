# kws-accelerator
# Keyword Spotting Accelerator

A small neural network that recognizes spoken words (up, down, left,
right), built as hardware in Verilog.

I train a model in Python, shrink it to 8-bit, rebuild it in Verilog,
and check that both give the same answers.

## Tools
Python, Verilog, Icarus Verilog, GTKWave, Vivado