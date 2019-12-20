# frequency_python
Determining frequency of reads and writes into CC compiler from din file containing 300K lines of code.

# (A)Frequency Problem
(a) You have to process one file, see below, and create a histogram that shows the number of occurences of the 2nd field in the file. On the Ox axis of the plot you will have the 2nd field in the file as a decimal number. On the Oy axis you will have the number of occurrences.

Here's the file:

cc1.din The file was produced by capturing the addresses used by the CPU when compiling the CC compiler. Each line in the file has two fields: the first field indicates what kind of operation the CPU performs (read, write, etc.), and the second field is the address as a hexadecimal number. Here is what the number in the first field means:

0: read data 1: write data 2: instruction fetch The second field is the address being referenced: the address is a hexadecimal byte-address between 0 and ULONG_MAX inclusively.

(b) What is the frequency of writes? What is the frequency of reads?
