<h1>TASK 1 - Bitwise  Functions</h1>
<p>Finish the implementation of the functions inside bit_ops.c</p>

<h1>TASK 2 - Linear Feedback Shift Register</h1>
<p>On each call to lfsr_calculate, you will shift the contents of the register 1 bit to the right.
● This shift is neither a logical shift or an arithmetic shift. On the left side, you will shift in a single bit
equal to the Exclusive Or (XOR) of the bits originally in position 0, 2, 3, and 5.
● The curved head-light shaped object is an XOR, which takes two inputs (a, b) and outputs a^b.
● If you implemented lfsr_calculate() correctly, it should output all 65535 positive 16-bit integers
before cycling back to the starting number.
● Note that the leftmost bit is the MSB and the rightmost bit is the LSB.
</p>