# MULTIPLIER WITH BCD OUTPUT
## Overview
 This repository contains the design of a multiplier circuit that exclusively comprises combinational circuits. It multiplies two 4-bit numbers and displays the output in BCD form on a seven-segment display. The conversion of the 8-bit binary output to BCD format is achieved using the *Double Dabble algorithm*.
 ## DOUBLE DABBLE ALGORITHM
 The double dabble algorithm is a computer science technique that converts binary numbers to binary-coded decimal (BCD) numbers. It's also known as the shift-and-add-3 algorithm.
 - (https://en.wikipedia.org/wiki/Double_dabble#:~:text=In%20computer%20science%2C%20the%20double,the%20expense%20of%20high%20latency.)
 ## ABOUT CIRCUIT
 - The circuit necessitates the manual selection of four bits from each of the two numbers to be multiplied.
 - The selected numbers are processed within the "MUL" sub-circuit, which performs the multiplication and generates an 8-bit output.
 - The output is then transmitted to the "BCD" sub-circuit, which employs the *Double Dabble algorithm* to convert the binary result into its Binary-Coded Decimal (BCD) representation.
 - Finally, the output from the BCD sub-circuit is fed into a seven-segment display, which presents the final computed result.
