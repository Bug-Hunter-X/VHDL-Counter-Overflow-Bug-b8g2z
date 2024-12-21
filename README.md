# VHDL Counter Overflow Bug

This repository demonstrates a common error in VHDL:  an integer counter that doesn't handle overflow. The `buggy_counter.vhdl` file contains the buggy code. The counter increments until it reaches the maximum value and continues to increment. The result is undefined, and could lead to unexpected behavior in a real implementation.

The `fixed_counter.vhdl` file provides a corrected version that handles the overflow condition correctly.