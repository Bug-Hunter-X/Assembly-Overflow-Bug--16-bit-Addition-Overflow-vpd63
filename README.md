# Assembly Overflow Bug
This repository demonstrates a common error in assembly programming: integer overflow. The `bug.asm` file contains code that adds two 16-bit registers. If the sum exceeds the maximum value for a 16-bit register (65535), an overflow occurs. The `bugSolution.asm` file provides a corrected version that handles potential overflows.  This example highlights the importance of considering potential overflows when working with integer arithmetic in assembly language.